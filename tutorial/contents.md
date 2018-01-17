Contents
=========

1. Goto Anything (Navigation)
------------------------------

1. Goto Anything: `Ctrl + P`
2. Goto Symbol: `Ctrl + R`
3. Goto Line: `Ctrl + G`


2. Editing text
----------------

1.  Insert line before / after - `Ctrl + Shift + Return` / `Ctrl + Return`
2.  Copy line / Paste from history - `Ctrl + C` / `Ctrl + K, Ctrl + V`
3.  Delete to beginning / end - `Ctrl + Shift + Backspace` / `Ctrl + K K`
4.  Delete / Cut a line - `Ctrl + Shift + K` / `Ctrl + X`
5.  Soft Undo / Redo - `Ctrl + U` / `Ctrl + Shift + U`
6.  Upper / lower case - `Ctrl + K, Ctrl + U` / `Ctrl + K, Ctrl + L`
7.  Joining Lines - `Ctrl + J`
8.  Bubble the line up / down - `Ctrl + Shift + up` / `Ctrl + Shift + down`
9.  Sort a line - `F9`
10. Duplicating a line - `Ctrl + Shift + D`
11. Indent - Unindent - `Ctrl + ]`, `Ctrl + [`
12. Commenting a line - `Ctrl + /`
13. Close HTML tag - `Alt + .`
14. Wrap line at ruler - `Alt + Q`
15. Transpose - `Ctrl + T`


3. Selection
-------------

1.  Multiple selection - `Ctrl + clicks at multiple places`
2.  Column Selection
    `Ctrl + Alt + Up` and `Ctrl + Alt + Down` (or `Alt + Shift + Up` and `Alt
     + Shift + Down` for Linux) or `Shift + Right-Mouse drag`/ `Esc` for going back to single
3.  Split block of selection into multiple lines - select a block of text, 
    then `Ctrl + Shift + L`
4.  Select word with multiple occurrences - `Ctrl + D`
    Quick skip - `Ctrl + K, Ctrl + D`
5.  Selecting a line - `Ctrl + L`
6.  Expand selection to brackets - `Ctrl + Shift + M`
7.  Expand selection to indentation - `Ctrl + Shift + J`
8.  Expand selection to scope - `Ctrl + Shift + Space`


4. Navigation
--------------

1.  Goto symbol in project - `Ctrl + Shift + R`
2.  Goto definition - `F12`
3.  Goto beginning / end of a line - `Home` / `End`
4.  Goto matching bracket - `Ctrl + M`
5.  Move back / forward in history - `Alt + -` / `Alt + Shift + -`
6.  Code fold / unfold - `Ctrl + Shift + [` / `Ctrl + Shift + ]`


5. Find
--------

1.  Find - `Ctrl + F`
    Find next - `F3`
    Find previous - `Shift + F3`
    Find all - `Alt + Return` (while find window is open)
    Use selection to find - `Ctrl + E`
2.  Incremental find - `Ctrl + I`
    Incremental find previous - `Ctrl + Shift + I`
    Find all with incremental find - `Alt + Return` (while the panel is open)
3.  Replace panel - `Ctrl + H`
    Replace next - `Ctrl + Shift + H`
    Replace all - `Ctrl + Alt + Return` (Only when replace panel is open)
    Add selection to replace - `Ctrl + Shift + E`
4.  Quick find - `Ctrl + F3`
    Quick find previous - `Ctrl + Shift + F3`
    Quick find all - `Alt + F3`
5.  Find in project - `Ctrl + Shift + F`


6. Others
----------

Opening User settings - `^ + ,`
Python Console - `^ + Backticks`
Command Palette - `Ctrl + Shift + P`


7. TODO
-------

 - Add information on Projects and Workspaces: http://docs.sublimetext.info/en/latest/file_management/projects.html
   - discuss File --> New Window (Shift + Ctrl + N) to create a new anonymous project, then Project --> Edit Project to set the project preferences (see here for format: https://www.sublimetext.com/docs/3/projects.html), then Project --> Save Project As... to save the project!
 - Discuss "Package Control: Install Package" via Ctrl + Shift + P
   - Nice packages to include are: 
     - Package Control
     - Sublime Tutor
     - Function Name Display
     - Outline
     - Print to HTML
     - Notepad++ Color Scheme
     - ExportHtml
       - See here if you'd like to print using Notepad++ Color Scheme colors: https://stackoverflow.com/questions/48087699/how-do-i-change-the-color-scheme-used-by-the-exporthtml-package-in-sublime-text
     - Compare Side-By-Side <--THIS ONE IS ESPECIALLY USEFUL
 - Add the extra "Goto Anything" Operator: "#". Ex: `Ctrl + ;` or adding "#" in a Goto Anything (Ctrl + P) command will allow you to perform a fuzzy search of the search term you write after, within the open file. See here: http://docs.sublimetext.info/en/latest/file_management/file_navigation.html#goto-anything


