# gitcheatsheet
How to upload a Jupyter notebook to your Github as a new repo
1.First you will need to make sure you have Git installed. Go to your command line and type git --version. If it gives you any type of error, then go to git-scm.com to download and install Git. 
2.Once Git is installed, create a local folder containing all of the content for your Jupyter Notebook (make a folder put your notebook in it). 
3.Open your terminal window (simply Terminal on Mac or Git Bash on Windows) and navigate to the folder location using cd file-path. 
4.Once you are in the folder, type git init . - your notebook is now under version control. 
5.Now you will type git add . to add all of the files to the staging area. 
6.And git commit -m "Initializing notebook" will take a snapshot of this version of the notebook. 
7.When you make changes, just do steps 5 and 6 again. At this point your notebook is versioned but now you need to get it on GitHub. 
8.Log in to GitHub.com and click the + sign on the top right corner to create a repository. 
9.Do not choose the option initialize with a readme. 
10.Once you click the Create Repository button, you will see instructions for how to upload your file onto GitHub. 
"""
print "Open your terminal or Git Bash in windows"
print "navigate to your Jupyter Notebook using: cd your path"
git init your file name
git add your file name
git commit -m
print "login to GitHub.com click the + sign to create a repository. do not choose to initialize with a readme"
print "now upload your file onto GitHub"

To add someone else’s tasty repo from the command line
1.	Cd into the directory folder you want to place the file 
2.	Type git clone and the file address like this: git clone https://github.com/reponame/Sunshine-Version-2.git
