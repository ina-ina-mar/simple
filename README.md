# Intro to GIT and Markdown

GUIs (Graphical User Interfaces) vs. command line
  
## **Unix commands**<br>
* **pwd** (print working directory) --> Users/ina --> shows you the path --> where you are<br>
* **ls** (list) --> lists of all the files and folders in directory you're currently at (e.g. users/ina)<br>
* **cd** (change directory) --> from current directory --> to new directory<br>
    -  . --> your current directory<br>
    - .. --> one directory up<br>
    - ~ (tilde) --> home directory<br>
    - cd simple<br>
    - pwd --> /users/ina/simple<br>
    - ls --> README.md<br>
    - how to get back? --> cd .. --> brings me one level up --> to home directory which contains simple directory<br>
    - get back to simple --> cd simple<br>
    - get to home directory --> tilde<br>
* **mkdir**<br>
    - ALWAYS pwd check WHERE you're currently at (before creating a new dir)<br>
    - if created (mkdir) in a wrong place and want to remove it --> e.g. created in a simple directory not in home directory or elsewhere:<br>
    - **rm -rf** "nazwa directory, które chcemy usunąć" ; rm -rf "emptydir"<br>
      mkdir emptydir<br>
* **clear** --> clears terminal<br>
* **mv [nazwa_pliku] [nazwa_folderu/]** --> to move file to directory (folder); use TAB for directory name search (the directory name is followed by slash); if the file you want to move is in a different place to your folder --> give the path to the folder<br>
* **git status** --> (red) --> file untracked ; (green) --> file tracked (after git add)
* **git add -m "add_pdf"** --> now git tracks the file
* **git commit**<br>
* **git fetch**<br>
* **git push**<br>
* **git pull**<br>

     
## **Shortcuts**<br>
  TAB --> fills in the rest of a name<br>
  UP arrow --> repeats the previous command<br>

## Command structure<br>
- **command -o --option arguments**<br>
  - options modify commands in some way
  - always put options BEFORE arguments
- **git config --list** --> **git config** is command and **--list** is option<br>
- **git config --global user.name "Ina Martyna"** --> **git config** = command ; **--global** = option for both arguments ; **user.name** and **"Ina Martyna"** = arguments; (space between Ina Martyna that's why "in quote")<br>
- **git commit -m "Marketing changes"** --> **git commit** = command; **-m** = one-letter option for a message<br>

## File Stages <br>
- **unstaged** --> local change to a file (adding or deleting a file) (like writing in your physical notebook)<br>
- **staged** --> marked local change as smth you want git to track --> you want to commit to save in git (like checkmarking on each page things you think you want to save)<br>
  * **git add**<br>
- **committed** --> committed the file --> the version is saved in git (like scanning the reviewed things from the notebook pages and storing them locally on my computer in a folder) <br>
  * **git commit**<br>
- **pushed** --> uploaded the file to the server so that others can access it --> in this case the server is git_hub (like sharing them with others) <br>
  * **git push** <br>



  









  
