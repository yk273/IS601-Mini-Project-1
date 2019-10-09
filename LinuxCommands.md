# Vi
* *vi* or *vim* is a text editor available in almost all Linux distributions, including Git Bash. This is the text editor used to write the files for this repository. *vi* can also accept markdown commands as well, providing the user with the ability to structure and style the data in a more coherent way.
* To create a file that can use *vi*, the syntax **touch (file name)** needs to be used, preferably a *.md* file (md stands for Markdown). Here is an example that shows a file being created in Git Bash.
![Touch Example](/images/touch.PNG)
* To enter the *vi* text editor, the syntax in the command line would be **vi (file name)**
![Vi Example 1](/images/vi_Part1.PNG)
* Once in the text editor the main keystrokes are:
	* *i* to go into *INSERT MODE*
	* *esc* to go into *COMMAND MODE*
	* To save what had been written on *INSERT MODE*, the user needs to switch to the *COMMAND MODE* and input *:x!* (if the user used a Windows machine while operating Git Bash) or *:wq* (if the user used a Linux/Mac machine while operating Git Bash)
* The following example shows the LinuxCommands.md file in vi on *INSERT MODE*
![Vi Example 2](/images/vi_Part2.PNG)

# Linux Commands 

## cd
* **cd**: Change Directory
* This command changes the working directory to the directory specified by the user. Here is an example of a current working directory, and how it can be changed within the command line. This will move the user "down" the directory.
![cd Example 1](/images/cd_Part1.png)
* Another way to navigate is moving "up" the directory. This is done by using **cd ../** to move the directory "up" by one, **cd ../..** to move the directory "up by two, etc.
![cs Example 2](/images/cd_Part2.png)

## mkdir
* **mkdir**: Make Directory
* This command creates a new directory specified with a name (directories can also be referred to as a folders). In this example, a new directory named "Pastels" in the folder "Mediums" is created. The command ls (which lists all files and and folders in the current directory) now lists "Pastels" among the other directories.
![mkdir Example](/images/mkdir.png)

## cp
* **cp**: Copy Files and Directories
* This command copies files to a location named by the last argument on its command line. If the target is an existing file, cp overwrites it; if it does not exist, cp creates it. The syntax is **cp (source file)(destination file)**. However that is not enough for the line to work: there needs to be an additional *option* input specifying what parts of the file to copy and how to copy them. For the follwing examples, a **-r** option is used, which will recursively copy a folder and create a copy.
* The first example shows the "Misc" folder being copied into the folder "Art Portfolios" (both are located in Desktop).
![cp Example 1](/images/cp_Part1.png)
* The second example shows the "Misc" folder being copied into the folder "Mediums" (one folder is up the directory while the other is down the directory).
![cp Example 2](/images/cp_Part2.png)

## pwd
* **pwd**: Print Working Directory
* This command prints the full system path of the current working directory.
![pwd Example](/images/pwd.png)

## mv 
* **mv**: Move Files and Directories
* This command moves files to another location. This is done by specifying the file/directory and the path you want it to take. Here is an example of moving a file from Desktop tothe "Portraits" directory.  
![mv Example 1](/images/mv_Part1.png)
* **mv** can also be used to rename files, as shown in the following example.
![mv Example 2](/images/mv_Part2.png)

## rm
* **rm**: Remove Files
* This command removes a file (or files) specified with a name (For directories the command is rmdir). This type of deletion is irretrievable and therefore final. In this example, the "MonaLisapng" is deleted from the "Portraits" directory.  
![rm Example](/images/rm_Edit.png)

## history
* **history**: Shows History
* This command shows a list of all commands that have been run in that terminal session. 
![history Example](/images/history.png)

## home directory and ~
* **~**: Home Directory
* This command returns the user's path back to the beginning (the default path that the user is introduced to when opening the command line). Using the syntax "cd ~", the user will get back to the default "home" directory. 
![Home Return Example](/images/home_return.png)

## file paths in linux
* A file path is a unique location to a file or folder within a file system on a computer. A path is determined by inputing the branches in order to reach the file or folder, seperated by **/**. There are two types of paths: an absolute and and a relative path
	* An absolute path is defined as the specifying the location of a file or directory from the root directory. Here is an example of a full absolute path.
![Absolute Path Example](/images/absolute_path.png)
	* A relative path is defined as path related to the present working directory. Here is an example of a relative path, from the working directory "Art_Portfolio"
![Relative Path Example](/images/relative_path.png)

## Using the tab key to complete file paths
* In command line, there is a way to complete a part of the line, and offers suggestions that can be displayed for a given executable. In the middle of writing part of the line, the user can press the **Tab** button and object will complete itself. In the following example, the user used **Tab** to finish "nixcraft.com", "google.com" and "cyberciti.biz".
![Tab Key Example](https://www.cyberciti.biz/media/new/faq/2018/11/Bash-host-command-auto-completion.gif)

## Using up and down arrow for history
* In command line, there is an easier way to write lines in command line that the user frequently writes. Instead of entering all that again and again, the user can quickly search their history to find the complete command just by using the up and down arrow keys. The following example shows this in effect.
![Arrow Key Example](https://i.stack.imgur.com/CrGBj.gif)

