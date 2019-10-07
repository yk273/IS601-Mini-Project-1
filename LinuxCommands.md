# Linux Commands 

### cd
* **cd**: Change Directory
* This command changes the working directory to the directory specified by the user. Here is an example of a current working directory, and how it can be changed within the command line. This will move the user "down" the directory.
![cd Example 1](/images/cd_Part1.png)
* Another way to navigate is moving "up" the directory. This is done by using **cd ../** to move the directory "up" by one, **cd ../..** to move the directory "up by two, etc.
![cs Example 2](/images/cd_Part2.png)

### mkdir
* **mkdir**: Make Directory
* This command creates a new directory specified with a name (directories can also be referred to as a folders). In this example, a new directory named "Pastels" in the folder "Mediums" is created. The command ls (which lists all files and and folders in the current directory) now lists "Pastels" among the other directories.
![mkdir Example](/images/mkdir.png)

### cp
* **cp**: Copy Files and Directories
* This command copies files to a location named by the last argument on its command line. If the target is an existing file, cp overwrites it; if it does not exist, cp creates it. The syntax is **cp (source file)(destination file)**. However that is not enough for the line to work: there needs to be an additional *option* input specifying what parts of the file to copy and how to copy them. For the follwing examples, a **-r** option is used, which will recursively copy a folder and create a copy.
* The first example shows the "Misc" folder being copied into the folder "Art Portfolios" (both are located in Desktop).
![cp Example 1](/images/cp_Part1.png)
* The second example shows the "Misc" folder being copied into the folder "Mediums" (one folder is up the directory while the other is down the directory).
![cp Example 2](/images/cp_Part2.png)

### pwd
* **pwd**: Print Working Directory
* This command prints the full system path of the current working directory.
![pwd Example](/images/pwd.png)

### mv 
* **mv**: Move Files and Directories
* This command moves files to another location. This is done by specifying the file/directory and the path you want it to take. Here is an example of moving a file from Desktop tothe "Portraits" directory.  
![mv Example 1](/images/mv_Part1.png)
* **mv** can also be used to rename files, as shown in the following example.
![mv Example 2](/images/mv_Part2.png)

### rm
* **rm**: Remove Files
* This command removes a file (or files) specified with a name (For directories the command is rmdir). This type of deletion is irretrievable and therefore final. In this example, the "MonaLisapng" is deleted from the "Portraits" directory.  
![rm Example](/images/rm_Edit.png)

### history
* **history**: Shows History
* This command shows a list of all commands that have been run in that terminal session. 
![history Example](/images/history.png)

### home directory and ~
* **~**: Home Directory
* This command returns the user's path back to the beginning (the default path that the user is introduced to when opening the command line). Using the syntax **cd ~**, the user will get back to the default "home" directory. 
![Home Return Example](/images/home_return.png)

### file paths in linux

### Using the tab key to complete file paths
* In command line, there is a way to complete a part of the line, and offers suggestions that can be displayed for a given executable. In the middle of writing part of the line, the user can press the **Tab** button and object will complete itself. In the following example, the user used **Tab** to finish "nixcraft.com", "google.com" and "cyberciti.biz".
![Tab Key Example](https://www.cyberciti.biz/media/new/faq/2018/11/Bash-host-command-auto-completion.gif)

### Using up and down arrow for history
* In command line, there is an easier way to write lines in command line that the user frequently writes. Instead of entering all that again and again, the user can quickly search their history to find the complete command just by using the up and down arrow keys. The following example shows this in effect.
![Arrow Key Example](https://i.stack.imgur.com/CrGBj.gif)

