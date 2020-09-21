# Text-Editor

## *What is a Text Editor*
 - A text editor is a program or system that allows you to edit a text which can be downloaded or accessed online. 
 - Using a text editor can help you build a website, which means it is the most usefull tool for a web developer
 - One great feature for text editing is code completion, using code completeion saves you time by providing you a choice instead of allowing you to finish and to encounter problems later.
- Another great feature of it is being able to write HTML and CSS effectively.
- Syntax highlighing is another great feature which lets you highlight **text**.
- Making themes which allow you to change colors of backgrounds and texts.
- Using extensions are like plugins for your text editor for minimal effort

## Using the software on your computer
. There are many other text editing software out there so why download another when you already have one? There are ones that could help you write better code or you could find it more fluid than others. This all depends on yourself if there are ones that you are use or you can try diffrent text editing programs that could help you do better. 


## Third Party Options 
. There are many applications that could be used from third party programs such as
     1. Notepad ++
     2. TextWrangler/BB Edit
     3. Visual Studio Code
     4. Atom
     5. Brackets
     
. Each of these programs support diffrent windows such as mac and linux and have their own unique path for more information visit [Third Party Options](https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf)    

## The Difference Between Text Editors and IDES
- A text editor already defines itself from the name of it as it edits texts.
- An IDE is (Integrated Development Environment)is a text editor, a file manager, a compiler, and a debugger all in one software package. For example such as Microsoft outlook how it has all its diffrent options right under one application. 

# **The Command Line**

- A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text. Here is a example of the command line 

1.user@bash:ls -l /home/ryan
2.total 3
3.drwxr-xr-x  2 ryan users 4096 Mar 23 13:34 bin
4.drwxr-xr-x 18 ryan users 4096 Feb 17 09:12 Documents
5.drwxr-xr-x  2 ryan users 4096 May 05 17:25 public_html
6. user@bash:

The following is the explantation
1.Line 1 presents us with a prompt ( user@bash ). After that we entered a command ( ls ). Typically a command is always the first thing you type. After that we have what are referred to as command line arguments ( -l /home/ryan ). Important to note, these are separated by spaces (there must be a space between the command and the first command line argument also). The first command line argument ( -l ) is also referred to as an option. Options are typically used to modify the behaviour of the command. Options are usually listed before other arguments and typically start with a dash ( - ).
2.Lines 2 - 5 are output from running the command. Most commands produce output and it will be listed straight under the issuing of the command. Other commands just perform their task and don't display any information unless there was an error.
3.Line 6 presents us with a prompt again. After the command has run and the terminal is ready for you to enter another command the prompt will be displayed. If no prompt is displayed then the command may still be running (you will learn later how to deal with this).

## The Shell Bash
- When you are in the terminal it is referred to as a shell this is part of the operating system which defines how the operating system behaves. 
- There are many shells avaliable but the most common one is called bash. If you would like to know which shell you are in you put the following **echo $Shell/bin/bash**

Another great way to quickly write text in the editor is knowing all of your short cuts. 

# Basic Navigation
- The first command we will be using is the **pwd** which is Print Working
- The second command we will be using is the ls and its a short cut for list

## Paths
- There are two diffrent pathing absolute and relative. And if you use any of the paths you will get the same result as they work on all text editors.
- The very top of these paths is the **root** and is denoted by using /

## More on pathing tools 
~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
. (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
.. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory


For more examples and informatio visit [Linux Tutorial](https://ryanstutorials.net/linuxtutorial/navigation.php)

# About Files
- Everything is a file. A text file is a file and a directory is a file everyhing is a file. 

The following are common extentions

. file.exe - an executable file, or program.

. file.txt - a plain text file.

. file.png, file.gif, file.jpg - an image.

More about files on [Linux Tutorial](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)


