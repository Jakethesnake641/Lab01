## Lab 01

- Name: Jacob Wing
- Email: wing.10@wright.edu

## Part 1 - GitHub Profile

1. [Jakethesnake641's Profile](FIXTHISURL-https://github.com/Jakethesnake641)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |  Display help documentation for commands      |
| Get-Location | pwd    |  	Print the current working directory      |
| Get-ChildItem | ls    |   	List files and directories in the current directory     |
| mkdir   | mkdir       |   	Create a new directory     |
| Set-Location | cd     |  	Change the current directory      |
| New-Item | touch      |   	Create a new file     |
| Move-Item | mv        |   	Move or rename a file/directory     |
| Copy-Item | cp        |  Copy a file or directory      |
| Remove-Item | rm      |    Delete a file or directory    |
| notepad.exe | vim     |   	Open a text editor     |

## Part 3 - Command Line Navigation

My OS is:
- [] Windows
- [x] Linux
- [] Mac

My Command Line Shell is: Bash

### Navigating My OS on the Command Line

### 1. Create a directory named DirA:
mkdir DirA

### 2. Create a directory named "Dir B" (with a space, requires quotes):
mkdir "Dir B"

### 3. Go into DirA:
cd DirA

### 4. Go into "Dir B" from DirA (assumes "Dir B" is at the same level as DirA):
cd ../"Dir B"

### 5. Return to your user's home directory:
cd ~

### 6. Create a file named test.txt:
touch test.txt

### 7. Move the file named test.txt into DirA:
mv test.txt DirA/

### 8. Add contents to test.txt:
echo "Put your words here" > DirA/test.txt

### 9. Make a copy of test.txt named copy.txt in DirA:
cp DirA/test.txt DirA/copy.txt

### 10. View the contents of DirA:
ls DirA

### 11. Make a copy of test.txt in "Dir B" named fodder.txt:
cp DirA/test.txt "Dir B/fodder.txt"

### 12. Delete / remove both fodder.txt AND "Dir B":
rm "Dir B/fodder.txt"
rmdir "Dir B"

