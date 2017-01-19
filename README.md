# The Idea

<p align="justify">Recently I have got this rare opportunity to work with two development environments simultaneously. Everything was going fine until it came to debugging. The server was written in C/C++ so I used Visual Studio 2015 to work it out, while the access console code was based on good old Java, in which case I used IntelliJ Idea. You can only imagine what a nightmare it was to check everytime what shortcut was binded to which action when the program reached some breakpoint.</p>

<p align="justify">Why on earth they cannot stick to the one keymap scheme on every IDE when the actions they provide do exacly the same stuff?</p>

<p align="justify">Things get even worse when you realize that default shortcuts (those, which I would like to use can be described in hundreads) are very close to being random.</p> 

<p align="justify">In IntelliJ Idea for example (which you should use in your daily job, really :)) you have Alt + 1 for Project View, but Ctrl + Shift + F12 for Terminal, what is kinda weird as both of them represent subwindow. How can I remember over 200 shortcuts that are barely related to each other? (and trust me, I tried)</p>

<p align="justify">So I came up with this idea to create universal list of shortcuts that are not only easy to remember but also pleasent to use. I dream about time, when keyboard shortcuts will be standarized. Just imagine. All cool functions available just like that.</p>

<p align="justify">I exported keymap scheme described below right from my IntelliJ installation, so feel free to download it and use if you like it. I would be more then excited to hear any feedback and objections.</p>

<p salign="justify">I have been working with these shortcuts for a while now, but I know some changes may be done to make it even more powerful.</p>

# How is it built?

<p align="justify">Well, I often feel quite stupid and I am not the best at remembering things. That's why I said to myself - "Divide all shortcuts in categories and make them general and simple so that most of IDEs can adopt them."</p>

<p align="justify">We often use non-numeric keybaords (e.g in laptops). This is the reason that any shortcut containing key from numeric part of keyboard is not allowed.</p>

<p align="justify">I am human and although I have five fingers per hand I don't wanna to use them all at the same time. So every shortcut can be composed of one main key and at most two functional keys. Sorry, I wouldn't remember G + Ctrl + Shift + Alt + "God knows what else" anyway.</p>

<p align="justify">There are only three functional keys allowed. Ctrl like "control behaviour". Shift like "shift behaviour". Alt like "alternate behaviour". Only shortcuts allowed without using functional keys are F1 - F12. Common, these keys were designed to serve as function keys, am I right?.</p>

---

# Debugging and Running

|Shortcut|Description|Shortcut|Description|Shortcut|Description|
|:--------|:-------------------------|:--------|:------------|:--------|:------------|
|**F1**|Enter/Exit fullscreen|**Ctrl + F1**|Distraction free mode|**Shift + Alt + F1**|Presentation mode|
|**F2**|
|**F3**|Build project|**Ctrl + F3**|Rebuild project|
|**F4**|Run/Rerun|**Ctrl + F4**|Terminate|**Shift + Alt + F4**|Choose to run|
|**F5**|Debug|**Ctrl + F5**|Pause|**Shift + Alt + F5**|Choose to debug|
|**F6**|Run configurations|
|**F7**|
|**F8**|Hot swap|
|**F9**|Line breakpoint|**Ctrl + F9**|Watch point|**Shift + Alt + F9**|Method breakpoint|
|**F10**|Step over|**Ctrl + F10**|Drop frame|**Shift + Alt + F10**|Force over|
|**F11**|Step into|**Ctrl + F11**|Step out|**Shift + Alt + F11**|Force into|
|**F12**|Run to cursor|||**Shift + Alt + F12**|Force to cursor|

---

# IDE Views

|Shortcut|Description|Shortcut|Description|
|:--------|:-------------------------|:--------|:-------------------------|
|**Ctrl + Shift + F1**|Project/Solution view|**Shift + F1**|Locate file in project view|
|**Ctrl + Shift + F2**|Favourites|**Shift + F2**|Add to favourites|
|**Ctrl + Shift + F3**|Operation results|
|**Ctrl + Shift + F4**|Run/Output|**Shift + F4**|Process list|
|**Ctrl + Shift + F5**|Debug|
|**Ctrl + Shift + F6**|TODO/Task list|
|**Ctrl + Shift + F7**|File structure view|**Shift + F7**|Structure dialog|
|**Ctrl + Shift + F8**|Version control|**Shift + F8**|VCS operations|
|**Ctrl + Shift + F9**|Breakpoints|
|**Ctrl + Shift + F10**|Database view|
|**Ctrl + Shift + F11**|Bookmarks|**Shift + F11**|Bookmarks dialog|
|**Ctrl + Shift + F12**|Terminal|

---

# Language specific tools views (Configure yourself)

|Shortcut|Description|Shortcut|Description|
|:--------|:-------------------------|:--------|:-------------------------|
|**Ctrl + Alt + F1**|Maven|
|**Ctrl + Alt + F2**|Gulp|**Alt + F2**|Gulp dialog|
|**Ctrl + Alt + F3**|
|**Ctrl + Alt + F4**|
|**Ctrl + Alt + F5**|
|**Ctrl + Alt + F6**|
|**Ctrl + Alt + F7**|
|**Ctrl + Alt + F8**|
|**Ctrl + Alt + F9**|
|**Ctrl + Alt + F10**|
|**Ctrl + Alt + F11**|
|**Ctrl + Alt + F12**|

---

# Bookmarking

|Shortcut|Description|Shortcut|Description|
|:--------|:-------------------------|:--------|:-------------------------|
|**Ctrl + 1**|Go to bookmark 1|**Ctrl + Shift + 1**|Toggle bookmark 1|
|**Ctrl + 2**|Go to bookmark 2|**Ctrl + Shift + 2**|Toggle bookmark 2|
|**Ctrl + 3**|Go to bookmark 3|**Ctrl + Shift + 3**|Toggle bookmark 3|
|**Ctrl + 4**|Go to bookmark 4|**Ctrl + Shift + 4**|Toggle bookmark 4|
|**Ctrl + 5**|Go to bookmark 5|**Ctrl + Shift + 5**|Toggle bookmark 5|
|**Ctrl + 6**|Go to bookmark 6|**Ctrl + Shift + 6**|Toggle bookmark 6|
|**Ctrl + 7**|Go to bookmark 7|**Ctrl + Shift + 7**|Toggle bookmark 7|
|**Ctrl + 8**|Go to bookmark 8|**Ctrl + Shift + 8**|Toggle bookmark 8|
|**Ctrl + 9**|Go to bookmark 9|**Ctrl + Shift + 9**|Toggle bookmark 9|
|**Ctrl + 0**|Go to bookmark 0|**Ctrl + Shift + 0**|Toggle bookmark 0|

---

# Refactoring

|Shortcut|Description|
|:--------|:-------------------------|
|**Ctrl + Alt + 1**|Rename symbol|
|**Ctrl + Alt + 2**|Rename file|
|**Ctrl + Alt + 3**|Change signature|
|**Ctrl + Alt + 4**|
|**Ctrl + Alt + 5**|
|**Ctrl + Alt + 6**|
|**Ctrl + Alt + 7**|
|**Ctrl + Alt + 8**|
|**Ctrl + Alt + 9**|
|**Ctrl + Alt + 0**|

---

# Git Options

|Shortcut|Description|
|:--------|:-------------------------|
|**Shift + Alt + 1**|Annonate|
|**Shift + Alt + 2**|Check current revision|
|**Shift + Alt + 3**|Show remotes|
|**Shift + Alt + 4**|Stash changes|
|**Shift + Alt + 5**|Commit changes|
|**Shift + Alt + 6**|Push changes|
|**Shift + Alt + 7**|Unstash changes|
|**Shift + Alt + 8**|Fetch changes|
|**Shift + Alt + 9**|Pull changes|
|**Shift + Alt + 0**|Branches|

---

# Coding

|Shortcut|Description|Shortcut|Description|Shortcut|Description|
|:--------|:-------------------------|:--------|:------------|:--------|:------------|
|**Ctrl + A**|Select all|**Ctrl + Shift + A**|Search action|**Ctrl + Alt + A**|Add file to index|
|**Ctrl + B**|Toggle bookmark|
|**Ctrl + C**|Copy selection|**Ctrl + Shift + C**|Copy path|
|**Ctrl + D**|Duplicate line|**Ctrl + Shift + D**|Diff|**Ctrl + Alt + D**|Diff history|
|**Ctrl + E**|Recent files|**Ctrl + Shift + E**|Recently edited|
|**Ctrl + F**|Find in file|**Ctrl + Shift + F**|Find in path|**Ctrl + Alt + F**|Format code|
|**Ctrl + G**|Go to line|**Ctrl + Shift + G**|Generate code|
|**Ctrl + H**|Class hierarchy|**Ctrl + Shift + H**|Method hierarchy|**Ctrl + Alt + H**|Call hierarchy|
|**Ctrl + I**|Implement methods|**Ctrl + Shift + I**|Implementations|
|**Ctrl + J**|Join lines|
|**Ctrl + K**|
|**Ctrl + L**|
|**Ctrl + M**|Move to cursor|
|**Ctrl + N**|Navigate to class|**Ctrl + Shift + N**|Navigate to file|**Ctrl + Alt + N**|To symbol|
|**Ctrl + O**|Override method|**Ctrl + Shift + O**|Optimize imports|
|**Ctrl + P**|Check parameters|
|**Ctrl + R**|Replace in file|**Ctrl + Shift + R**|Replace in path|**Ctrl + Alt + R**|Refactor this|
|**Ctrl + Q**|Quick documentation|**Ctrl + Shift + Q**|Quick definition|**Ctrl + Alt + Q**|Quick type|
|**Ctrl + S**|Save file|**Ctrl + Shift + S**|Show usages|**Ctrl + Alt + S**|Show advanced|
|**Ctrl + T**|Insert template|**Ctrl + Shift + T**|Surround with|**Ctrl + Alt + T**|Go to tests|
|**Ctrl + U**|Upper/lower case|**Ctrl + Shift + U**|Up in hierarchy|**Ctrl + Alt + U**|UML diagram|
|**Ctrl + V**|Paste clipboard|**Ctrl + Shift + V**|Paste from history|
|**Ctrl + W**|Widen selection|**Ctrl + Shift + W**|Shrink selection|
|**Ctrl + X**|Cut selection|
|**Ctrl + Y**|Erase line|
|**Ctrl + Z**|Undo|**Ctrl + Shift + Z**|Redo|
|**Ctrl + >**|Fold/Unfold block|
|**Ctrl + /**|Comment line|**Ctrl + Shift + /**|Comment selection|
|**Ctrl + {**|Go to "{" bracket|**Ctrl + Shift + {**|Select all to bracket|
|**Ctrl + }**|Go to "}" bracket|**Ctrl + Shift + }**|Select all to bracket|
							
# Special keys

|Shortcut|Description|Shortcut|Description|
|:--------|:-------------------------|:--------|:------------|
|**Ctrl + Right**|Move right by symbols|**Ctrl + Shift + Right**|Select symbol to the right|
|**Ctrl + Left**|Move left by symbols|**Ctrl + Shift + Left**|Select symbol to the left|
|**Ctrl + Up**|Scroll editor up|**Ctrl + Shift + Up**|Switch line, block or method up|
|**Ctrl + Down**|Scroll editor down|**Ctrl + Shift + Down**|Switch line, block or method down|
|**Ctrl + Insert**|Insert new file|**Ctrl + Shift + Insert**|Open file in new window|
|**Ctrl + Space**|Code completion|**Ctrl + Shift + Space**|Intelligent completion|
|**Ctrl + Tab**|Switcher|
|**Ctrl + Enter**|Split line|**Ctrl + Shift + Enter**|Perform IDE suggested action|
|**Ctrl + Backspace**|Delete symbol to cursor|**Ctrl + Shift + Backspace**|Last edit location|
|**Ctrl + Delete**|Delete symbol from cursor|			
|**Ctrl + Home**|Move caret to the start|**Ctrl + Shift + Home**|Move caret and select content|
|**Ctrl + End**|Back to editor|**Ctrl + Shift + End**|Move caret and select content|

---

# Others

|Shortcut|Description|Shortcut|Description|
|:--------|:-------------------------|:--------|:-------------------------|
|**Esc**|Back to editor|
|**Tab**|Indent|**Shift + Tab**|Unindent|
