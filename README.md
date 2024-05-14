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
![Screenshot 2024-05-14 104546](https://github.com/jeffybrailin/Windows-basic-commands-batchscript/assets/146911326/053c5483-edca-4f40-940d-b1555322ca6e)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

![Screenshot 2024-05-14 104717](https://github.com/jeffybrailin/Windows-basic-commands-batchscript/assets/146911326/ab426aaf-a90c-4036-9227-63a75f408234)


![Screenshot 2024-05-14 104852](https://github.com/jeffybrailin/Windows-basic-commands-batchscript/assets/146911326/1631f16c-16ed-4bd6-a634-d67ff1a37e91)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![Screenshot 2024-05-14 104944](https://github.com/jeffybrailin/Windows-basic-commands-batchscript/assets/146911326/3e46b794-578a-4bfb-b986-b9f195779289)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

![Screenshot 2024-05-14 105032](https://github.com/jeffybrailin/Windows-basic-commands-batchscript/assets/146911326/a0f29b9c-fbd7-44d6-aa18-5805334df0f1)


![Screenshot 2024-05-14 105119](https://github.com/jeffybrailin/Windows-basic-commands-batchscript/assets/146911326/57fc68fb-ccfd-4273-8d56-a5277340a220)

## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!

## OUTPUT

![Screenshot 2024-05-14 105407](https://github.com/jeffybrailin/Windows-basic-commands-batchscript/assets/146911326/39a4ab5e-1bb2-4952-b13c-fe4d3cb1cf71)


# RESULT:
The commands/batch files are executed successfully.

