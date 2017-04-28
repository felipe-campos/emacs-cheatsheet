# Emacs Cheatsheet

### Buffer & Files
|Key Binding|Description|
|-----------|-----------|
|**C-x b**  |Switch buffer (pick in the minibuffer)|
|**C-x b**  |Create new buffer (enter a new buffer name)|
|**C-x C-f**|Open a file (navigate to the file)|
|**C-x C-f**|Create new file (enter new file's path)|

### Navigatin Text
|Key Binding|Description|
|-----------|-----------|
|**C-a**|Move to beginning of line|
|**M-m**|Move to first non-whitespace character on the line|
|**C-e**|Move to end of line|
|**M-f**|Move forward one word|
|**M-b**|Move backward one word|
|**M-<**|Move to beginning of buffer|
|**M->**|Move to end of buffer|
|**M-g g**|Go to line|
|**C-s**|Regex search for text in current buffer and move to result. Press **C-s** again to move to next match|
|**C-r**|Same as **C-s** but search in reverse|

### Killing & Yanking Text (aka Copy & Paste)
|Key Binding|Description|
|-----------|-----------|
|**C-w**|Cut selected text – kill region|
|**C-y**|Paste – yank|
|**M-d**|Cut word after point – kill word after point|
|**C-k**|Cut line after point – kill line after point|
|**M-w**|Copy selected text — copy region to kill ring|
|**M-y**|Change pasted text to “next item on clipboard” — cycle through kill ring after yanking|

### Run Commands
|Key Binding|Description|
|-----------|-----------|
|**M-x _function-name_**|Run command by name|
|**M-x package-list-packages**|List packages available|
|**M-x package-refresh-contents**|Update list of packages available|
|**M-x package-install**|Install packages|

### Run Commands
|Key Binding|Description|
|-----------|-----------|
|**C-h f**|Describe function|
|**C-h k _key-binding_**|Describe the function bound to the key binding|

### Frame & Windows
|Key Binding|Description|
|-----------|-----------|
|**C-x o**|Switch cursor to another window|
|**C-x 0**|Delete current window|
|**C-x 1**|Delete all other windows|
|**C-x 2**|Split frame vertically|
|**C-x 3**|Split frame horizontally|

### Clojure Major Mode
|Key Binding|Description|
|-----------|-----------|
|**C-c C-k**|Compile current buffer|
|**C-c M-n**|Switch to namespace of current buffer|
|**C-x C-e**|Evaluate expression immediately preceding point|

### Cider
|Key Binding|Description|
|-----------|-----------|
|**M-x cider-jack-in**|Start a nREPL for the current project and connect to it|
|**M-x cider-restart**|Quit CIDER and restart it|

### Paredit Minor Mode
|Key Binding|Description|
|-----------|-----------|
|**C-M-b**|Move to the opening parenthesis|
|**C-M-f**|Move to the closing parenthesis|
|**M-(**|Wrapping: <code>(+ 1 &#124;2 3)</code> => <code>(+ 1 (&#124;2) 3)</code>|
|**C-→**|Slurping: <code>(+ 1 (&#42; &#124;2) 3)</code> => <code>(+ 1 (&#42; &#124;2 3))</code>|
|**C-←**|Barfing: <code>(+ 1 (&#42; &#124;2 3 4))</code> => <code>(+ 1 (&#42; &#124;2 3) 4)</code>|
