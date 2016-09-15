## Introduction

- Show Presentation Assist Plugin and demonstrate that it shows Hotkeys on the bottom.
- Explain that i'm using IntelliJ but has almost all the same functionality as PHPStorm.
- Bare with me as I will most likely show you things that you already know, but others might not.
- The key of the presentation is to show you the capabilities that this IDE offers.
- Of course you aren't going to remember everything, so just try to remember what your IDE is capable of doing, and the rest will take time.
- Feel free to speak up if you know something interesting because I might forget or not even know.
- Made a github readme of everything we will be talking about so don't be scared if you missed something, I will share it after this.
- Try your best to avoid touching your mouse and learn shortcut hotkeys that the IDE has.
- Feel free to interrupt me any time for questions.

> Talk about User Interface of IDE

1. Editor <kbd>ESC</kbd>
2. Project Navigator <kbd>CMD</kbd> <kbd>1</kbd>
3. Version Control <kbd>CMD</kbd> <kbd>9</kbd>
4. Terminal <kbd>ALT</kbd> <kbd>F12</kbd>
5. Navigation Bar <kbd>CMD</kbd> <kbd>↑</kbd>
6. Preferences <kbd>CMD</kbd> <kbd>,</kbd>
7. Searching

- Pressing ESC will always take you back to the editor
- hold <kbd>SHIFT</kbd> <kbd>CMD</kbd> and LEFT or RIGHT to scale down current window
- In my opinion, I suggest removing the top toolbar as it takes up space
- We can actually do everything in our toolbar with hotkeys
- I only use it for git, but I just remember <kbd>CTRL</kbd> + <kbd>V</kbd> and press the number w/o touching the mouse.

> Talk About Project Navigator

## Project Navigator

- Quickly go to your project window by typing in <kbd>CMD</kbd> <kbd>1</kbd> and go back to you code editor by pressing <kbd>ESC</kbd>.
- You can search for any files by just typing while you are in the project window.
- You can choose to show only your changed files.
- You can choose to show by `Structure` <kbd>CMD</kbd> <kbd>7</kbd> instead of by files. This is useful if you are in a huge file and just want to see seperated class names, methods, functions, and so on.
- Click the `target` for it to immediately point you to your current file opened in your code editor.
- Click the `collapse` to collapse all files and folders to root.
- One useful thing is the `Autoscroll from source` which automatically moves to the current file that you are editing in your code editor.

> Talk about Advantages of using version control on this IDE

## Version Control

- You can quickly open up version control by pressing <kbd>CMD</kbd> <kbd>9</kbd>
- Quickly see version control operations with <kbd>CTRL</kbd> <kbd>V</kbd>
- Choose a way to update your project with <kbd>CMD</kbd> <kbd>T</kbd>
- Shows Git Log visually and you can select each commit to compare differences.
- You can use annotate to see who has changed something previously
- See all your local changes.
- You can create a changelist to make sure those files will not be commited.
- See Differences between local and previously committed files.
- When you get a merge conflict, we can fix easily by right clicking the file -> Git -> Fix Merge Conflict (The best feature in my opinion)


> Discuss Editor Basics

## Editor

### Basic Shortcut Keys

#### 1. Moving the Cursor


| Description | Shortcut Key |
| --- | --- |
| Moving your cursor to the next or previous line | <kbd>CTRL</kbd> <kbd>N</kbd> or <kbd>CTRL</kbd> <kbd>P</kbd> |
| Moving to end or beginning of the line of code | <kbd>CMD</kbd> <kbd>←</kbd> or <kbd>CMD</kbd> <kbd>→</kbd> |
| Moving forward in line of code | <kbd>CTRL</kbd> <kbd>F</kbd> |
| Moving backward in line of code | <kbd>CTRL</kbd> <kbd>B</kbd> |
| Moving word by word in line of code | <kbd>ALT</kbd> <kbd>←</kbd> or <kbd>ALT</kbd> <kbd>→</kbd> |


#### 2. Selecting Code


| Description | Shortcut Key |
| --- | --- |
| Highlight the next occurrence of highlighted code | <kbd>CMD</kbd> <kbd>G</kbd> |
| Highlight the previous occurrence of highlighted code | <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>G</kbd> |
| Highlight same code occurrence with | <kbd>CTRL</kbd> <kbd>G</kbd> or <kbd>CTRL</kbd> <kbd>SHIFT</kbd> <kbd>G</kbd> |
| Highlight code based on its grammar and enclosed blocks of code | <kbd>ALT</kbd> <kbd>↑</kbd> or <kbd>ALT</kbd> <kbd>↓</kbd> |
| Highlight a character at a time | <kbd>SHIFT</kbd> <kbd>←</kbd> or <kbd>SHIFT</kbd> <kbd>→</kbd> |
| Highlight up or down line by line of code | <kbd>SHIFT</kbd> <kbd>↑</kbd> or <kbd>SHIFT</kbd> <kbd>↓</kbd> |
| Highlight the rest of the line of code on the right or left side | <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>←</kbd> or <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>→</kbd> |
| Highlight each by word and punctuation | <kbd>CMD</kbd> <kbd>SHIFT</kbd> <kbd>←</kbd> or <kbd>CMD</kbd> <kbd>SHIFT</kbd> <kbd>→</kbd> |
 
 
#### 3. Manipulating Code


| Description | Shortcut Key |
| --- | --- |
| Duplicate your current highlighted code | <kbd>CMD</kbd> <kbd>D</kbd> |
| Move the current line of code up | <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>↓</kbd> <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>↑</kbd> |
| Comment or uncomment a line of code | <kbd>CMD</kbd> <kbd>/</kbd> |
| Comment or uncomment a multi-line of code | <kbd>CMD</kbd> <kbd>ALT</kbd> <kbd>/</kbd> |
| Expand or collapse a code block | <kbd>CMD</kbd> <kbd>+</kbd> or <kbd>CMD</kbd> <kbd>-</kbd> |
| Surround with highlighted code with something | <kbd>ALT</kbd> <kbd>CMD</kbd> <kbd>T</kbd> |
| Reformat or line code up | <kbd>CMD</kbd> <kbd>ALT</kbd> <kbd>L</kbd> |
| Delete whole line | <kbd>CMD</kbd> <kbd>DELETE</kbd> |
| Smart Line Joining, Pressing multiple times will keep joining the lines. | <kbd>CTRL</kbd> <kbd>SHIFT</kbd> <kbd>J</kbd> |
| Create new lines without moving the cursor | <kbd>CMD</kbd> <kbd>ENTER</kbd> |
| Toggle Letter Case and you can even toggle multilines.| <kbd>CMD</kbd> <kbd>SHIFT</kbd> <kbd>U</kbd> |
| Paste selected entry from the Clipboard to the caret location | <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>V</kbd> |
| Deleting the word starting from the current caret location up to the word end | <kbd>ALT</kbd> <kbd>DELETE</kbd> |


#### 4. Other Useful Shortcuts


| Description | Shortcut Key |
| --- | --- |
| Create a new file and more | <kbd>CMD</kbd> <kbd>N</kbd> |
| Quickly go to usage or find multiple usages | <kbd>CMD</kbd> <kbd>B</kbd> |
| Retrieve Parameter Information | <kbd>CMD</kbd> <kbd>P</kbd> | 
| Find more documentation on highlighted (double tap detailed documentation) | <kbd>CTRL</kbd> <kbd>J</kbd> |
| Show intention actions and quick fixes | <kbd>ALT</kbd> <kbd>ENTER</kbd> |
| Navigate between opened tabs | <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>]</kbd> or <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>[</kbd> |
| Navigate through tabs with history | <kbd>CMD</kbd> <kbd>[</kbd> or <kbd>CMD</kbd> <kbd>]</kbd>  |
| Close active editor tab | <kbd>CMD</kbd> <kbd>W</kbd> |
| Scale your current window | <kbd>SHIFT</kbd> <kbd>CMD</kbd> and ```move with arrow keys``` |


#### 5. Using The Mouse


| Description | Shortcut Key |
| --- | --- |
| You can use your mouse to spread multiple cursors around your code | Hold <kbd>ALT</kbd> and Move mouse | 
| See more information about the piece of code by holding | Hold <kbd>CMD</kbd> and Hover mouse over code |
| Going directly to code's definition | Hold <kbd>CMD</kbd> and click code |

> Talk about Code Completion

### Code Completion

- If you want to see Basic Code Completion suggestions you can press <kbd>CTRL</kbd> <kbd>SPACE</kbd>
- It will show suggestions for variables, types, methods, expressions, and more.
- We also have Statement Completion it will add missing parentheses, brackets, braces, and other necessary formatting with <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>ENTER</kbd>
- You can also press enter if your code completion suggestion is first in the list to automatically insert.
- Hippie Completion (Cycles through keywords, class names, methods, or variables within the file) with <kbd>ALT</kbd> <kbd>/</kbd> don't know if anyone uses this, I just always type it in.


> Talk About Searching

#### 1. Shortcut Hotkeys for Searching

| Description | Shortcut Key |
| --- | --- |
| Find something in your current file | <kbd>CMD</kbd> <kbd>F</kbd> |
| Find and replace in current file | <kbd>CMD</kbd> <kbd>R</kbd> |
| Find in Path | <kbd>CMD</kbd> <kbd>SHIFT</kbd> <kbd>G</kbd> |
| Find and Replace in Path | <kbd>CMD</kbd> <kbd>SHIFT</kbd> <kbd>R</kbd> |
| Find a Class to go to | <kbd>CMD</kbd> <kbd>O</kbd> |
| Find a file to go to | <kbd>CMD</kbd> <kbd>SHIFT</kbd> <kbd>O</kbd> |
| Find a symbol to go to | <kbd>CMD</kbd> <kbd>ALT</kbd> <kbd>O</kbd> |
| Find a line number in current file and jump to it | <kbd>CMD</kbd> <kbd>L</kbd> |
| Find an action or option name | <kbd>CMD</kbd> <kbd>SHIFT</kbd> <kbd>A</kbd> |
| Search Everywhere! | Double Tap <kbd>SHIFT</kbd> |

- Normally I either use only `Search Everywhere` or `Find an Action`

- Filter your search by clicking the gear icon to only look in specific areas.
- Search by Regex, by whole words, or turn on case sensitivity.
- Search with wildcards(*) for example ```*Block.php or Block.* or *Page*.js or List*Page*.js```
- Search by each letter in file name.
- Search file with and jump to line number when opened. For Example ```server.js:40```
- Search for structural blocks/templates with by finding an action and look for ```Search Structurally``` you can also replace a block of code with ```Replace Structurally```.

--- Talk About Emmet ---

### Emmet (http://emmet.io/)

- Our IDE includes Emmet by default. It is a plugin that increases your code editing workflow.
- Includes HTML, CSS, and XSL fast on tab snippets!
- Go to the website and read the documentation, it is pretty worth it.
- Their cheatsheet is at (http://docs.emmet.io/cheat-sheet/)

- show some html examples of making a lists with links
    - show quick divs with .className or #idName
    - ul>li.my-class*5

- show how easy it is to remember css emmet 
    - explain that you don't really need to remember by demonstrating ```mt10px or pb50px or dib or tac```
    - test everyone to see if they can guess display inline-block;
    - "ul#nav>li.item$*4>{Item $}"

> Talk about how they can check how productive they are using the IDE

## Productivity Guide

- Since its built in, you can see your productivity guide by going to Help -> Productivity Guide
- Shows how much time you have saved using code completion has saved you.
- Shows you how many possible bugs that the IDE has saved you from.
- Shows all IDE features that are related to productivity and how many times you have used it.
- Shows information on how to use it.

> Talk about helpful terminal commands

- Move word by word when moving the cursor of the command with <kbd>ALT</kbd> <kbd>←</kbd> for forward and <kbd>ESC</kbd> <kbd>→</kbd> for backwards.
- Move at the end of the line or beginning with <kbd>CTRL</kbd> <kbd>E</kbd> or <kbd>CTRL</kbd> <kbd>A</kbd>
- Run multiple commands in one line `git add . && git commit 'commit test' && git push origin master`
- To clear window `clear`
- To cancel what you entered <kbd>CMD</kbd> <kbd>C</kbd>
- View contents of a file with `cat filename`
- Previous command `!ssh` to show previous command that we used that began with `ssh`
- Navigation through folders with `cd` pressing tab finish off what you were searching for
- See a list of commands you've previously entered `history`
- Undo something with <kbd>CTRL</kbd> <kbd>-</kbd>
- Show previous single commands by also using the up and down arrows on your keyboard also.
- Do a search between all your commands with <kbd>CMD</kbd> <kbd>R</kbd>
- Want to always see hidden files? Use: `defaults write com.apple.finder AppleShowAllFiles -bool TRUE` and false if you want to turn that off.

> Fun Commands

- We can make our Mac talk to us with `say 'Hello Codetony'`


> If there is time talk about zsh

- open source, community-driven framework for managing your ZSH configuration. It comes bundled with a ton of helpful functions, helpers, plugins, and themes

2. zsh
    - `http://ohmyz.sh/`
    - `https://github.com/robbyrussell/oh-my-zsh`
    - `https://github.com/robbyrussell/oh-my-zsh/wiki`
    - `https://github.com/robbyrussell/oh-my-zsh/wiki/Cheatsheet`

> If you have time, show how to increase Memory limit if the IDE is lagging

- Go to HELP -> Edit Custom VM Options
- Copy:

    ```
        -Xms128m
        -Xmx2048m
        -XX:MaxPermSize=350m
        -XX:ReservedCodeCacheSize=64m
        -XX:+UseCodeCacheFlushing
        -XX:+UseCompressedOops
    ```