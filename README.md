# Vim-fman
[fman](https://fman.io) plugin for vim-like movements and file operations.

## Usage
Note: capital letter means `shift + [key]`

### Movements
 * `h` goes up a directory.
 * `l` opens the currently selected directory or file.
 * `j` moves cursor up one
 * `k` moves cursor down one
 * `g`  move cursor to the top
 * `G` move cursor to bottom
 * `ctrl + d` move cursor one page down
 * `ctrl + u` move cursor one page up
 * `ctrl + o` move to previous directory
 * `ctrl + i` move to next directory
 
 ### Operations
 * `a` creates and edits a new file
 * `A` creates a new directory
 * `d` move the file to trash
 * `y` copy the file or directory under the cursor
 * `p` paste the file or directory in current directory
 * `P` paste the file or directory in current directory and **remove the original file**(paste-cut)
 * `r` rename the file or directory
 * `m` move the file or directory
 * `v` toggle selection
 * `o` open the file or directory with specific application, p.s. this can be used to open the folder in VScode, terminal, iterm, sublime text, or potentially anything else.

### Miscellaneous
 * `Y` copy the path of current file to the clipboard
 * `ctrl + l` open current directory or the directory under the cursor in right panel
 * `ctrl + h` open current directory or the directory under the cursor in left panel


This is inspired by VimNavigation plugin for fman.

## Installation

Install with [fman's built-in command for installing plugins](https://fman.io/docs/installing-plugins).

## Problems

Note that filter on type function of fman will be interfered by this plugin. You can consider using [FuzzySearchFilesInCurrentFolder](https://github.com/kszcode/FuzzySearchFilesInCurrentFolder) instead to search files in current folder.
