# It's about time you thought about being a productive coder.

Learn how to be more productive in the any JetBrains IDE.

- Note: you can go back to your code editor area by pressing the <kbd>ESC</kbd> key. 
- Note: To close the current window that you are on, you can press the same shortcut key again.

> I will break this lesson up into the IDE's components

1. Editor <kbd>ESC</kbd>
    - Basic Shortcut Keys
    - Emmet
    - Code Completion
2. Project Window <kbd>CMD</kbd> <kbd>1</kbd>
3. Version Control <kbd>CMD</kbd> <kbd>9</kbd>
4. Debugging <kbd>CMD</kbd> <kbd>5</kbd>
5. Terminal <kbd>ALT</kbd> <kbd>F12</kbd>
6. Navigation Bar <kbd>CMD</kbd> <kbd>UP</kbd>
7. Preferences <kbd>CMD</kbd> <kbd>,</kbd>
8. Inspections

## Editor
### Basic Shortcut Keys

> Use these in your code editor to increase coding productivity

- Move the current line of code up <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>UP</kbd> or down <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>UP</kbd> shortcut keys.
- Duplicate your current highlighted code with <kbd>CMD</kbd> <kbd>D</kbd>
- Comment or uncomment a line of code <kbd>CMD</kbd> <kbd>/</kbd>
- Find something in your current file with <kbd>CMD</kbd> <kbd>F</kbd>
- Find and replace in current file with <kbd>CMD</kbd> <kbd>R</kbd>
- Move the next occurance of highlighted code with <kbd>CMD</kbd> <kbd>G</kbd>
- Move the previous occurance of highlighted code with <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>G</kbd>
- Highlight same code occurance with <kbd>CTRL</kbd> <kbd>G</kbd> or go back with <kbd>CTRL</kbd> <kbd>SHIFT</kbd> <kbd>G</kbd> 
- Navigate between opened tabs <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>]</kbd> or <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>[</kbd>
- Navigating back and forth with history <kbd>CMD</kbd> <kbd>]</kbd> or <kbd>CMD</kbd> <kbd>[</kbd>
- Expand or collapse a code block with <kbd>CMD</kbd> <kbd>+</kbd> or <kbd>CMD</kbd> <kbd>-</kbd>
- Move your cursor to the next or previous line with <kbd>CTRL</kbd> <kbd>N</kbd> or <kbd>CTRL</kbd> <kbd>P</kbd> you can also use arrow keys, but your hand moves too far away.
- Create a new file and more with <kbd>CMD</kbd> <kbd>N</kbd>
- Surround with highlighted code with something <kbd>ALT</kbd> <kbd>CMD</kbd> <kbd>T</kbd>
- Code highlight something based on its grammar <kbd>ALT</kbd> <kbd>UP</kbd> or <kbd>ALT</kbd> <kbd>UP</kbd>
- Highlight a character at a time with <kbd>SHIFT</kbd> <kbd>LEFT</kbd> OR <kbd>SHIFT</kbd> <kbd>RIGHT</kbd>
- Highlight up or down line by line of code with <kbd>SHIFT</kbd> <kbd>UP</kbd> or <kbd>SHIFT</kbd> <kbd>DOWN</kbd>
- Highlight the rest of the line of code on the right or left side with <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>LEFT</kbd> or <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>RIGHT</kbd>
- Highlight enclosed blocks of code with <kbd>ALT</kbd> <kbd>UP</kbd> or <kbd>ALT</kbd> <kbd>DOWN</kbd>
- Highlight each by word and punctuation with <kbd>CMD</kbd> <kbd>SHIFT</kbd> <kbd>LEFT</kbd> or <kbd>CMD</kbd> <kbd>SHIFT</kbd> <kbd>RIGHT</kbd>
- Highlight code usages in a file with <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>F7</kbd>
- Go to end of the line of code with <kbd>ALT</kbd> <kbd>LEFT</kbd> or <kbd>ALT</kbd> <kbd>RIGHT</kbd>
- You can use your mouse to highlight multiple lines or have multiple cursors by holding <kbd>ALT</kbd> and with your mouse click and hold.

### Emmet (http://emmet.io/)

- Our IDE includes Emmet by default. It is a plugin that increases your code editing workflow.
- Includes HTML, CSS, and XSL fast on tab snippets!
- Go to the website and read the documentation, it is pretty worth it.
- Their cheatsheet is at (http://docs.emmet.io/cheat-sheet/)

### Code Completion

- If you want to see Basic Code Completion suggestions you can press <kbd>CTRL</kbd> <kbd>SPACE</kbd>
- It will show suggestions for variables, types, methods, expressions, and more.
- Most of the time, I use Smart Code Completion instead with <kbd>CTRL</kbd> <kbd>UP</kbd> <kbd>SPACE</kbd>
- We also have Statement Completion it will add missing parentheses, brackets, braces, and other necessary formatting with <kbd>SHIFT</kbd> <kbd>CMD</kbd> <kbd>ENTER</kbd>
- You can also press enter if your code completion suggestion is first in the list to automatically insert.
- Hippie Completion (Cycles through keywords, class names, methods, or variables within the file) with <kbd>ALT</kbd> <kbd>/</kbd> don't know if anyone uses this, I just always type it in.

## Project Window

- Quickly go to your project window by typing in <kbd>CMD</kbd> <kbd>1</kbd> and go back to you code editor by pressing <kbd>ESC</kbd>.
- You can search for any files by just typing while you are in the project window.
- You can choose to show only your changed files.
- You can choose to show by `Structure` instead of by files. This is useful if you are in a huge file and just want to see seperated class names, methods, functions, and so on.
- Click the `target` for it to immediately point you to your current file opened in your code editor.
- Click the `collapse` to collapse all files and folders to root.
- One useful thing is the `Autoscroll from source` which automatically moves to the current file that you are editing in your code editor.
 
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


## USEFUL Hot Keys
- hold shift cmd and arrow keys to scale down window





> Optional Steps:

1. IDE too slow? We can increase its memory limit in the VM Options.

 - `http://stackoverflow.com/questions/13578062/how-to-increase-ide-memory-limit-in-intellij-idea-on-mac`
 - `https://blog.jetbrains.com/idea/2006/04/configuring-intellij-idea-vm-options/`
 
> How to Get Started with this Repository:

    ~  git clone url
    ~  cd in/project
    ~  npm i
    ~  npm start
    