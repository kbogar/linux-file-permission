# File permissions in Linux

## Project description
The research team at my organization needs to update the file permissions for certain files and directories within the projects directory. The permissions do not currently reflect the level of authorization that should be given. Checking and updating these permissions will help keep their system secure. To complete this task, I performed the following tasks:

## Check file and directory details
The following code demonstrates how I used Linux commands to determine the existing permissions set for a specific directory in the file system.

![](/docs/linux1.png)

The first line of the screenshot displays the command I entered, and the other lines display the output. The code lists all contents of the **projects** directory. I used the **ls** command with the **-la** option to display a detailed listing of the file contents that also returned hidden files. The output of my command indicates that there is one directory named **drafts**, one hidden file named **.project_x.txt**, and five other project files. The 10-character string in the first column represents the permissions set on each file or directory.