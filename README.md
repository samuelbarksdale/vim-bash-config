# vim-bash-config
My awesome vim and bash configs
Using VIM

Moving Around
* h moves the cursor one character to the left.
* j moves the cursor down one line.
* k moves the cursor up one line.
* l moves the cursor one character to the right.
* 0 moves the cursor to the beginning of the line.
* $ moves the cursor to the end of the line.
* w move forward one word.
* b move backward one word.
* G move to the end of the file.
* gg move to the beginning of the file.
* `. move to the last edit.

Editing
* d starts the delete operation.10k
* dw will delete a word.
* d0 will delete to the beginning of a line.
* d$ will delete to the end of a line.
* dgg will delete to the beginning of the file.
* dG will delete to the end of the file.
* u will undo the last operation.
* Ctrl-r will redo the last undo.

Pasting and Highlighting 
* v highlight one character at a time.
* V highlight one line at a time.
* Ctrl-v highlight by columns.
* p paste text after the current line.
* P paste text on the current line.
* y yank text into the copy buffer.

Refactor: :%s/wordToReplace/replaceWith/g/

require 'pry';binding.pry
