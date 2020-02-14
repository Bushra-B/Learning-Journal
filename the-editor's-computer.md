# Text editors

**Text editors are softwares used to write and edit text either for documents or for coding.  
Text editors can be either downloaded and installed on your device, or accessed online through web browsers.  
It is an essential tool for programmers and web developers and so it should be chosen thoughtfully, but the choice of the text editor is merely personal.  
You can use the text editor software that comes with your computer, i.e. Notepad, or use a third-party software.**

## Code text editors are very important because they come with great features such as:

* code completion  
      This feature is highly important and it saves a lot of time because it provides you with choices and suggestions to complete the code statement you're typing, it also includes the closing of tags, brackets and quotation marks when you open them.
      
* syntax highlighting  
     This feature makes your code easier to read by colorizing the text such that different elements, attributes, etc have different colors
     
* different themes  

* Ability to add extensions  
     You can add more features to your text editor to meet your growing needs using extensions.
     
## Best options for third-party text editor for coding softwares:
- Notepad ++
- BB Edit
- Visual Studio Code (VSC)
- Atom
- Brackets
- Sublime Text

## Text editors Vs. IDEs:
An IDE (acronym for Integrated Development Environment) is a programming tool that is kind of a *sotware package* that contains a text editor, a file manager, a compiler/interpreter and a debugger.  
You use text editors to edit your code, while you can use an IDE to do all the work related to your project, from editing the code, running the code, debugging, visualizing UIs, etc.  
So in general text editors and IDEs can be used interchangeably, but with IDEs you can do a lot more than with text editors.

-----------------------------------------------------------------------

# Terminals / Command line interface

## The command line
**A terminal or a command line is a text-based interface to the system, in which you can navigate your operating system by typing text commands and executing them.  
In the command line, commands are typed at *prompts* and are the first thing to type after the prompt.  
After the command, you can type a command-line argument which _must_ be separated from the command by spaces.  
The first command-line argument (aka *option*) starts with a dash and modifies the behavior of the command.  
The output from running the command will be listed under the issuing of the command.  
But note that some commands don't display any information.**

## The shell:
**Within the terminal there is the *shell* which is a part of the operating system.**  
**The shell defines the behavior of the terminal and defines how the terminal will look after executing the commands.**  
- `echo` command is used to know which shell you're using.  

*shortcut tip*: commands are stored in history, so you can use the up and down arrow keys to get the commands you previously typed.

## Important commands:
**These commands are available in Linux, macOS and Windows (with WSL)**  
* `pwd`  
Stands for Print Working Directory: use this to know where you are currently (what your current or present working directory is) 
    - it's important to know where you currently are when you're making commands because some commands depend on the location when excuted.
    - `pwd` command doesn't need argument.
    
* `ls`   
Which is short for list: use this to list the contents of a directory
    - this is how you know what is there in the in the location you are in.
    
    - `ls` command can run with arguments and without arguments.
    
    - arguments (options) can be used with `ls` command as:  `ls -option location`
    
* `cd`  
Which stands for Change Directories: use this to move to another directory as:   `cd location`

## Paths:
**A location, whether it is a file or a directory, is refered to on the command line using a _path_.  
Paths are what are used to get to a particular location (file or directory) on the system.**  

— The *root* directory:  
the root directory is like the top-level directory in a file system, which has subdirectories, which in turn have subdirectories and so on.  
any file may be in any of these directories.  
the root directory is denoted by a (/) in the begining of its directory name.  

*Note*: the commad `cd ..` is used to move back to the root directory  

**Types of paths:**
1. absolute path  
       - specifies a location (file/directory) in relation to the root directory  
       - begins with a (/)
       
2. relative path  
       - specifies a location (file/directory) in relation to the current directory we are at in the system  
       - does not begin with a (/)
