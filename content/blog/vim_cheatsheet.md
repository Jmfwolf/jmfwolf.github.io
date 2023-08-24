---
title: "Vim Cheatsheet"
date: 2023-08-23
publishDate: 2023-08-23
tags: ["software development"]
comments: false
---

## Basic Modes:

1. **Normal mode (Command mode)**: This is the default mode when you open a file. You can navigate, manipulate, and issue commands in this mode.
2. **Insert mode**: You can enter this mode to modify the file.
3. **Visual mode**: Select text.

## Mode Switching:

- **i**: Enter insert mode before the cursor.
- **I**: Enter insert mode at the beginning of the line.
- **a**: Enter insert mode after the cursor.
- **A**: Enter insert mode at the end of the line.
- **o**: Open a new line below the current line and enter insert mode.
- **O**: Open a new line above the current line and enter insert mode.
- **ESC**: Return to normal mode from any other mode.

## Navigation:

- **h**: Left
- **j**: Down
- **k**: Up
- **l**: Right
- **w**: Next word
- **b**: Previous word
- **^**: Start of line
- **$**: End of line
- **G**: Go to the last line
- **gg**: Go to the first line
- **[number]G**: Go to [number] line. (e.g., `5G` takes you to the 5th line)

## Editing:

- **x**: Delete character under the cursor.
- **X**: Delete character before the cursor.
- **dd**: Delete entire line.
- **dw**: Delete word from cursor to end of word.
- **D**: Delete from cursor to end of line.
- **u**: Undo last action.
- **Ctrl + r**: Redo.
- **yy or Y**: Yank (copy) the current line.
- **yw**: Yank the word.
- **p**: Paste after the cursor.
- **P**: Paste before the cursor.

## Searching:

- **/pattern**: Search for pattern.
- **n**: Find next occurrence of pattern.
- **N**: Find previous occurrence of pattern.
- **?pattern**: Search for pattern backwards.
  
## Replacing:

- **:s/old/new**: Replace first occurrence of 'old' with 'new' in the current line.
- **:s/old/new/g**: Replace all occurrences of 'old' with 'new' in the current line.
- **:%s/old/new/g**: Replace all occurrences of 'old' with 'new' in the entire file.
- **:%s/old/new/gc**: Replace all occurrences with confirmation.

## File Handling:

- **:w**: Save (write) the file.
- **:w filename**: Save as 'filename'.
- **:q**: Quit `vi`.
- **:q!**: Quit without saving.
- **:wq** or **ZZ**: Save and quit.
  
## Miscellaneous:

- **:set number**: Show line numbers.
- **:set nonumber**: Hide line numbers.
- **:split**: Split the window horizontally.
- **:vsplit**: Split the window vertically.
- **Ctrl + w + w**: Switch between windows.