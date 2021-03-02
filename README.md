# Git-flow-basico
Datos masivos --- Git-flow-basico --- 1/March-21

1) Create github account

2) Install git in the terminal using sudo apt install git (use git --version to see if it work)

3) Create an ssh key using ssh-keygen -t ed25519 -C "alejandro.castro17@tectijuana.edu.mx" 
  * When the text - Enter a file in which to save the key (/home/you/.ssh/id_ed25519): [Press enter] - Just press enter
  * Use eval `ssh-agent -s` to manage the ssh key and later use ssh-add ~/.ssh/name
  * Use clip < ~/.ssh/id_ed25519.pub to copy the ssh key
  * In github settings SSH key, make a new key name it and later paste the ssh key  
 
4) Configure git by assigning your user name "Ale2C" and your email "alejandro.castro17@tectijuana.edu.mx" 

5) Create a folder and assing its dirrectory in the terminal ex:
  * ls (To see the contents of the directory that youre using)
  * cd (To assign the directory you want to use=
  
6) Make a repository in github in the repository window (You can create a readme file in the bottom of the confimation page)

7) Copy the SSH code to clone it in the directory you assign using git clone and the SSH code 

8) Make a new branch in github in the small panel of branchs or in the terminal using git branch nameofthebranch
  * To know the branchs you have use git branch or git show-branch

9) To change branch in terminal use git checkout nameofbranch

10) Create or edit a file using git commit 

11) Use git push to apply the changes

12) Use git pull to "receive" or update the files that were changed 
  
