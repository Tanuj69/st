# Dracula themed suckless terminal build with scroll

The [suckless terminal (st)](https://st.suckless.org/) with some additional features that make it literally the best terminal emulator ever:

## Unique features (using dmenu)

+ **follow urls** by pressing `alt-l`
+ **copy urls** in the same way with `alt-y`
+ **copy the output of commands** with `alt-o`

## Bindings for

+ **scrollback** with `alt-↑/↓` or `alt-pageup/down` or `shift` while scrolling the mouse
+ OR **vim-bindings**: scroll up/down in history with `alt-k` and `alt-j`. Faster with `alt-u`/`alt-d`.
+ **zoom/change font size**: same bindings as above, but holding down shift as well. `alt-home` returns to default
+ **copy text** with `alt-c`, **paste** is `alt-v` or `shift-insert`

## Pretty stuff

+ Default font is system "mono" at 16pt, meaning the font will match your system font.
+ Very useful keybinds including:
	+ Copy is alt-c, paste is alt-v or alt-p pastes from primary selection
	+ Alt-l feeds all urls on screen to dmenu, so they user can choose and
	  follow one (requires dmenu installed).
	+ Zoom in/out or increase font size with Alt+Shift+k/j or u/d for larger intervals.
	+ Hold alt and press either ↑/↓ or the vim keys k/j to move up/down in the terminal.
	+ Shift+Mouse wheel do the same.
	+ Alt-u and Alt-d scroll back/forward in history a page at a time.
	+ Alt-PageUp and Alt-PageDown will do the same.
+ Vertcenter
+ Scrollback
+ Compatibility with `Xresources` and `pywal` for dynamic colors. The `Xdefaults` file shows a usage example.

## Other st patches

+ Vertcenter
+ Scrollback
+ updated to latest version 0.8.2


To be clear about the color settings:

- This build will use Dracula colors by default and as a fallback.
- If there are Xresources colors defined, those will take priority.
- But if `wal` has run in your session, its colors will take priority.

