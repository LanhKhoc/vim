# My vim cheat sheat

### Shortcut
- w: Jump forwards to the start of a word
- W: Jump forwards to the start of a word (Include punctuation {","; "."; "-"})
- e: Jump forwards to the end of a word
- E: - W: Jump forwards to the end of a word (Include punctuation {","; "."; "-"})
- r: Replace a character
- R: Replace a word
- tx: Jump to before next occurence of character x
- Tx: Jump to after previous occurence of character x
- yw: Copy a word at cursor
- yy: Copy a line
- y$: Copy from cursor to the end of line
- y^: Copy from cursor the the begin of line
- u: Undo action
- U: Undo all action of the line
- i: Insert before cursor
- o: Insert a line after cursor
- O: Insert a line before cursor
- p: Paste the clipboard after cursor
- P: Paste the clipboard before cursor
- a: Insert after cursor
- A: Insert at the end of line
- s: Delete character and enable insert mode
- S: Delete line and enable insert mode (Same cc)
- D: Delete (Cut) from the cursor to the end of line
- dw: Delete (Cut) a word from the cursor to the end of word
- daw: Delete (Cut) a word around cursor
- dd: Delete (Cut) whole line
- d$: Delete from the cursor to the end of line (Same D)
- d^: Delete from the cursor the the begin of line
- fx: Jump to next occurence of character x
- Fx: Jump to previous occurence of character x
- gg: Jump to the begin of file
- G: Jump to the end of file
- 5G: Jump to the line 5 of file
- g_: Jump to the last non-blank of line
- h: Move cursor left
- j: Move cursor down
- k: Move cursor up
- l: Move cursor right
- &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;k
- &nbsp;&nbsp;&nbsp;h&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;l
- &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;j
- zz: Center cursor on screen
- x: Delete character at cursor
- cc: Change (Replace) a line
- cw: Change (Replace) a word at cursor
- c$: Change (Replace) from the cursor to the end of line
- c^: Change (Replace) from the cursor to the begin of line
- v: Visual mode
- b: Jump backwards to the start of a word
- B: Jump backwards to the start of a word (Include punctuation {","; "."; "-"})
- n: Repeat search with same direction (Next or Previous)
- N: Repeat search with opposite direction (Previous or Next)
- mx: Mark current position to x
- `x: Jump to position of marked x
- <<: Shift text left with 1 tab
- >>: Shift text right with 1 tab




##### Visual Mode:
- aw: Select a word
- ab: Select a block inside () and include ()
- aB: Select a block inside {} and include {}
- d: Delete selected
- ib: Select a block inside () and dont include ()
- iB: Select a block inside {} and dont include {}
