# MW
This is a custom command to move the vim undo files together with the actual files.
It's not perfect. One better solution would be to modify the **coreutils mv** source file.

# Links
- http://vimdoc.sourceforge.net/htmldoc/options.html#'undodir'
- https://git.savannah.gnu.org/cgit/coreutils.git
- https://en.wikipedia.org/wiki/Mv#Examples

# How to use
1. Follow [this](https://vi.stackexchange.com/questions/6/how-can-i-use-the-undofile) answer
2. Update *VIM_UNDO_FILE* on line 7 with your undodir path 
3. Make it executable: *chmod +x mw*
4. Make it system-wide: *mv mw /usr/bin*
