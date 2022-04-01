## After Installation, You Need To
- Install pip3, and do pip3 install --user pynvim
- Install node, and do npm install -g neovim

## Keyboard Shortcuts
### Basic Editor Features
##### 1.1 The Most Basic
`h` : switchs to **`INSERT`** : mode (same as key `i` in vanilla vim)\
**`Q`** : quits current vim window (same as command `:q` in vanilla vim)\
**`S`** : saves the current file (same as command `:w` in vanilla vim)\
`jk`: Escape from terminal input mode

##### 1.2 Remapped Cursor Movement
Shortcut|Action|Equivalent
------------|------------|---------
`i`|Cursor up|`k`
`k`|Cursor down|`j`
`j`|Cursor left|`h`
`l`|Cursor right|`l`
`I`|Cursor up 5 terminal lines|`5k`
`K`|Cursor down 5 terminal lines|`5j`
`N`|Cursor to the start of the line|`0`
`M`|Cursor to the end of the line|`$`
`n`|Move to the end of this word|`e`

##### 1.3 Remapped Text Manipulating Commands in Normal Mode
Shortcut|Action
------------ | ------------
`<`|Un-indent
`>`|Indent

##### 1.5 Other Useful Normal Mode Remappings
Shortcut|Action
------------ | ------------
`r`|**Compile/Run the current file**
`Y`|copy till the end of the line
`SPACE` `s` `c`|Spelling Check
`SPACE` `/`|Create a new terminal below the current window
`SPACE` `o`|Fold
##### 1.6 Remapped Commands in Visual Mode
Shortcut|Action
------------ | ------------
`Y`|Copy selected text to system clipboard

### Window Management
##### 2.1 Creating Window Through Split Screen
Shortcut|Action
------------ | ------------
`s` `i`|Create a new horizontal split screen and place it above the current window
`s` `k`|Create a new horizontal split screen and place it below the current window
`s` `j`|Create a new vertical split screen and place it left to the current window
`s` `l`|Create a new vertical split screen and place it right to the current window
`s` `h`|Set the two splits to be horizontal
`s` `v`|Set the two splits to be vertical
`s` `r` `h`|Rotate splits and arrange splits horizontally
`s` `r` `v`|Rotate splits and arrange splits vertically

##### 2.2 Moving the Cursor Between Different Windows
Shortcut|Action
------------ | ------------
`SPACE` + `j`|Move cursor one window left
`SPACE` + `l`|Move cursor one window right
`SPACE` + `i`|Move cursor one window up
`SPACE` + `k`|Move cursor one window down

##### 2.3 Resizing Different Windows
Use the arrow keys to resize the current window.

##### 2.4 Closing Windows
Shortcut|Action
------------ | ------------
`Q`|Close the current window
`Space q`|Close the window below the current window. (The current window will be closed if there is no window below)

### 3 Tab Management
Shortcut|Action
------------ | ------------
`ti`|Create a new tab
`t` `j`|Go one tab left
`t` `l`|Go one tab right
`t` `m` `j`|Move tab left
`t` `m` `l`|Move tab right
## Plugins Keybindings
### [coc(AutoCompletion)](https://github.com/neoclide/coc.nvim)
Shortcut|Action
------------ | ------------
`Space` `y`|**Get yank history list**
`Space` `h`|Show documentation in preview window
`gd`|Go to definition
`gr`|List references
`gi`|List implementation
`gy`|Go to type definition
`ts`|Coc translator
`rn`|Coc rename
`Space d`|get all Coc diagnostics
`Space -`|previous Coc diagnostic
`Space =`|next Coc diagnostic

### [coc-explorer(file browser)](https://github.com/weirongxu/coc-explorer)
Shortcut|Action
------------ | ------------
`tt`|Go to CocCommand explorer
`?`|show help (in explorer)

### [rnvimr - file browser](https://github.com/kevinhwang91/rnvimr)
Press `R` to open Ranger (file selector)

And Within rnvimr (ranger), you can:
Shortcut|Action
------------ | ------------
`Ctrl` `t`|Open the file in a new tab
`Ctrl` `x`|Split up and down with the file
`Ctrl` `v`|Split left and right with the file

##### [FZF - the fuzzy file finder](https://github.com/junegunn/fzf.vim)
Shortcut|Action
------------ | ------------
`Ctrl` `p`|**FZF Files**
`Ctrl` `i`|Move up 1 item
`Ctrl` `k`|Move down 1 item
`Ctrl` `w`|FZF Buffers
`Ctrl` `f`|FZF Files' Content
`Ctrl` `h`|FZF Recent Files
`Ctrl` `t`|FZF Tags

##### [commentary.vim](https://github.com/tpope/vim-commentary)
Shortcut|Action
------------ | ------------
`gcc`|comment out a line (takes a count)
`gc`|comment out the target of a motion
