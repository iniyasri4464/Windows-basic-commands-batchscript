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
![image](https://github.com/iniyasri4464/Windows-basic-commands-batchscript/assets/152419072/f77bbb7c-b2b6-498d-b196-b54a8b8807d1)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![image](https://github.com/iniyasri4464/Windows-basic-commands-batchscript/assets/152419072/0ca4cf82-d682-4225-a7ad-eec255a50a2c)
![image](https://github.com/iniyasri4464/Windows-basic-commands-batchscript/assets/152419072/b0694343-c052-49c3-9ea5-6acb6aeb7e1d)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![image](https://github.com/iniyasri4464/Windows-basic-commands-batchscript/assets/152419072/d58e51a6-009f-4324-b581-1d77180d8e05)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![image](https://github.com/iniyasri4464/Windows-basic-commands-batchscript/assets/152419072/b4f9934f-3d00-4189-b7d7-ccd158ceb288)
![image](https://github.com/iniyasri4464/Windows-basic-commands-batchscript/assets/152419072/7437322f-6ba4-41d7-b9cc-7c9d64d4fd20)


## COMMAND AND OUTPUT
![image](https://github.com/iniyasri4464/Windows-basic-commands-batchscript/assets/152419072/ff459c30-fdbd-46c8-9b44-4b3afe31420f)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!






## OUTPUT
![image](https://github.com/iniyasri4464/Windows-basic-commands-batchscript/assets/152419072/1e854af0-79af-452a-9f5d-9dc8b8b05434)





# RESULT:
The commands/batch files are executed successfully.

