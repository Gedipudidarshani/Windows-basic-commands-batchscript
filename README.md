# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
%userprofile%\Desktop\MyLab
```
```
darshanig@Darshani-laptop:~$ mkdir %darshanig%\Desktop\MyLab
```
## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
%userprofile%\Desktop\MyLab
```
```
darshanig@Darshani-laptop:~$ cd %darshanig%\Desktop\MyLab
darshanig@Darshani-laptop:~/%darshanig%DesktopMyLab$ touch MyFile.txt
```
## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
dir %userprofile%\Desktop\MyLab
```
```
darshanig@Darshani-laptop:~/%darshanig%DesktopMyLab$ dir %darshanig%\Desktop\MyLab
darshanig@Darshani-laptop:~/%darshanig%DesktopMyLab$ cp MyFile.txt ~/Desktop/Backup/
darshanig@Darshani-laptop:~/%darshanig%DesktopMyLab$ ls MyFile.txt
MyFile.txt
```

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup 
```
```
darshanig@Darshani-laptop:~/%darshanig%DesktopMyLab$ mkdir -p ~/Desktop/Backup
darshanig@Darshani-laptop:~/%darshanig%DesktopMyLab$ file ~/Desktop/Backup
darshanig@Darshani-laptop:~/%darshanig%DesktopMyLab$ ls ~/Desktop/MyLab
darshanig@Darshani-laptop:~/%darshanig%DesktopMyLab$ ls ~/Desktop
MyLab
```


## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents
```
```
darshanig@Darshani-laptop:~/%darshanig%DesktopMyLab$ mv ~/Desktop/MyLab ~/Documents/
darshanig@Darshani-laptop:~/%darshanig%DesktopMyLab$ ls
%darshanig%DesktopBackup  %darshanig%Documents
```


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.







## OUTPUT





# RESULT:
The commands/batch files are executed successfully.

