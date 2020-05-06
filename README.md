# Simple Vim Command Cheatsheet

A cheatsheet to enable inexperienced users to navigate Vim with a mouse and without learning too many shortcuts

## Enabling the mouse

When you first enter Vim type `:` (colon) and then the following:
```
set mouse=a
```

## Modes

Vim has three modes: normal mode (to run commands), insert mode (to type text), and visual mode (to select text, etc)

You can always know what mode you are in by looking at the _bottom-left corner_.

**Pressing `Esc` (multiple times if necessary) will always take you back to _normal mode_**

## Editing text

### Delete selected text
Press `x`

### Copy selected text
Press `y` (short for "yank")

### Paste selected text
Press `P` (uppercase P, in normal mode to paste directly at the cursor, lowercase p to paste after the cursor)

## Terminals

Open a terminal with `:ter` in normal mode (read below for more details)

### Run Vim commands in a terminal
Press `Ctrl-W` to run Vim commands inside a terminal

### How to scroll a terminal with a mouse
Press `Ctrl-W` then `N` (uppercase N), then you'll be able scroll and select text in your terminal. **Press `i` (lowercase i) to go back to normal terminal mode**.

## View splits/windows
Splitting new panes into files and terminals are different, consult the respective section.

### Splitting file editing windows

#### Side-by-side
To split side-by-side press type the following in normal mode `:`
```
:vsplit
```
(`:vs` is a shorthand)

#### Split into top and bottom
To split into a top and bottom type the following in normal mode `:`
```
:split
```
(`:sp` is a shorthand)

### Splitting into terminal windows

#### Terminal above the current window
Type the following in normal mode
```
:terminal
```
(`:ter` is a shorthand)

#### Terminal adjacent to the current window
Type the following in normal mode
```
:vertical terminal
```
(`:vert ter` is a shorthand)

<!-- vim:set textwidth=0 wrap: -->

