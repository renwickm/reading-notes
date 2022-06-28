# Class 2 Reading Notes!

## Text Editor

What is a text editor?
>A piece of software that you download and install on your computer, or you access online through your web browser, that allows you to write and manage text, especially the text that you write (The Older Coder, *Choosing A Text Editor,* Jan. 11)

What features should you look for in a text editor?
1. Code Completion
>When typing in your code, code completion feature recognizes possible suggestions from what you started typing.
2. Syntax Highlighting
>Makes the the text you've typed more noticeable by colorizing the text.
3. A nice variety of themes (to reduce eye strain and fatigue)
>Themes allow you to change the color and scheme of the background. 
>>*Note: to reduce eye fatigue, use a darker color background scheme with brighter text.*
4. The ability to choose from a healthy selection of extensions available when you need them.
>Extensions are added features and/or tools that your text editor may utilize. Some text editors offer more extensions than others. While they aren't always necessary, they can make your codeing a lot easier.

>***Other features are available, but the most notible features are listed above.***

### Third-Party Options

1. NotePad++
2. TextWrangler/BB Edit
3. Visual Studio Code
4. Atom
5. Brackets
6. Sublime Text

### Text Editor and IDEs

**What is an IDE**
>An IDE (Integrated Development Environment) is a suite of different software all coming together (The Older Coder, *Choosing A Text Editor,* Jan. 11)
>It is a platform or workspace that has the ability to perform many, closely-tied and/or relatable, functions.

# The Command Line!

What is the Command Line?
-Also known as a ***Terminal*** , the Command Line acts as a GUI (Graphical User Interface) but adds functionality to the task/s you are doing
>Capable of having multiple windows open and working at once.
>While you don't, and probably won't, be using multiple windows at the same time, this allows you to bounce back and forth between tasks as they become prioritized.

-A text based interface to the system.
>Typing commands on the keyboard will provide feedback in text.

## Opening a Terminal

1. Mac users
>**Applications**, **Utilities**. 
>Or use the shortcut by hitting **command + space**. 
>In the spotlight search **Terminal**.
2. Linux users
>**Applications**, **System**, or **Applications**, **Utilities**,
>May be able to right-click on the desktop and there may be an option for ***Open in Terminal***.
3. Windows users
>Will need an SSH client.  
>***recommended***: Putty (Free)

## The Shell, Bash

What is a Shell?
>This is part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you (Chadwick, R. *The Command Line*, 2022).  
>Lives within the terminal

### Common Shells

1. Bash
>**B**ourne **a**gain **sh**ell

### Which are you using?

1. Echo
>In order to find which shell you are using, utilize the command ***echo*** in the command line, or terminal.  
>After the prompt, type **echo** for your command. Leave a spce between your command and line argument which is **$SHELL**.  
>It should look something like this: user@bash:  echo $SHELL  
>And will produce something like this: **/bin/bash**  
>>This output indicates you are using the shell ***bash***.

# Basic Navigation!

Where are you?
-**pwd*, or **p**rint **w**orking **d**irectory, lets you know what your present or current working directory is.  
-It's your current location

What's in your current location?
-**ls**, or **l**i**s**t, lists everything that is in the directory you are working in.

Path's
