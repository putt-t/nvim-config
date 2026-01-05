# Navigation and Search
Space+sf: search files
Space+sg: search by grep (search text in files)
Space+sh: search help docs
Space+sk: search keymaps
Space+sd: search diagnostics (errors/warnings)
Space+sn: search neovim config files
Space+sr: resume last search
Space+s.: search recent files
Space+/: fuzzy search in current buffer
Space+s/: search in open files

# LSP Navigation
grd: go to definition
grr: go to references
gri: go to implementation
grD: go to declaration (e.g., C header)
grt: go to type definition
gO: open document symbols (list all symbols in file)
gW: open workspace symbols (search symbols in project)
Ctrl+t: jump back from definition
Ctrl+o: jump back to previous location
Ctrl+i: jump forward

# Code Actions and LSP
K: show hover documentation
grn: rename symbol
gra: code actions (quick fixes)
Space+f: format buffer
Space+th: toggle inlay hints
Space+q: open diagnostic quickfix list
[d: go to previous diagnostic
]d: go to next diagnostic
Space+e: show diagnostic in floating window

# Git Commands
:Telescope git_status: see all changed files
:Telescope git_commits: see commit history
# Basic Motions
hjkl: left, down, up, right
w: jump forward by word
b: jump backward by word
0: beginning of line
$: end of line
gg: top of file
G: bottom of file
Ctrl+d: scroll down half page
Ctrl+u: scroll up half page
{: jump to previous paragraph
}: jump to next paragraph
# Editing
i: insert mode before cursor
a: insert mode after cursor
o: new line below and insert
O: new line above and insert
dd: delete line
yy: copy line
p: paste after cursor
P: paste before cursor
u: undo
Ctrl+r: redo
ciw: change inner word
diw: delete inner word
vi{: select inside curly braces
ci": change inside quotes
# Visual Mode
v: enter visual mode (character)
V: enter visual mode (line)
Ctrl+v: enter visual block mode
gc: toggle comment (in visual mode)
# Window Management
Ctrl+w s: split window horizontally
Ctrl+w v: split window vertically
Ctrl+w w: switch between windows
Ctrl+w h/j/k/l: move to left/down/up/right window
Ctrl+w q: close current window
# File Operations
:w: save file
:q: quit
:wq: save and quit
:q!: quit without saving
:e filename: open file
# Autocomplete
Ctrl+Space: trigger completion menu (while in insert mode)
Ctrl+n: next completion
Ctrl+p: previous completion
# Spell Checking (for markdown files)
]s: jump to next misspelled word
[s: jump to previous misspelled word
z=: show spelling suggestions for word under cursor
zg: add word to dictionary (mark as good)
zw: mark word as wrong/misspelled
zug: undo add to dictionary
# Other Useful Commands
gcc: comment current line
/search_term: search forward
?search_term: search backward
n: next search result
N: previous search result
*: search for word under cursor
.: repeat last command
%: jump to matching bracket
