# Linking-Pre-existing-R-project-with-GitHub
Linking a pre-existing RProject with GitHub
Linking an existing Project with Git

Linking an existing Project with Git
So what if you already have an R Project that you’ve been working on, but don’t have it linked up to any version control software

So first, let’s set up a situation where we have a local project that isn’t under version control. Go to File > New Project > New Directory > New Project and name your project. Since we are trying to emulate a time where you have a project not currently under version control, do NOT click “Create a git repository”. Click Create Project.

![image](https://user-images.githubusercontent.com/59471339/113389865-53470080-93c3-11eb-8847-79ded401e5ad.png)

Creating a project that is not under version control

We’ve now created an R Project that is not currently under version control. Let’s fix that. First, let’s set it up to interact with Git. Open Git Bash or Terminal and navigate to the directory containing your project files. Move around directories by typing ["cd ~/dir/name/of/path/to/file"]
![image](https://user-images.githubusercontent.com/59471339/113389961-78d40a00-93c3-11eb-82c8-56da781de37f.png)

[##Open Gitbash (this is not related with your previous guidelines, this is rather an independent explanation how to change directory)

#check existing directory by typing "pwd" which stands for Present Working Directory

#If you want to change it type "cd ~/gulmu/Doccuments/" 

#this will change to new directory.

#No need to write whole directory

#Forexample, if current directory is /c/Users/gulmu

#then don't type like this  "cd ~/c/Users/gulmu/specdata/Pollutant mean"

#Because it didn't work in my case.

#Just type "cd ~/specdata/Pollutantmean

#If you want to change to different drive (e.g., C drive to D drive), then type [cd "/d/R-files/Linking an existing Project with Git/"]
(we just inserted "directory" double appostrophe around directory 
]


Linking the project folder with Git so it is now under version control

At this point, we have created an R Project and have now linked it to Git version control. The next step is to link this with GitHub.



Linking this project with GitHub
To do this, go to GitHub.com, and again, create a new repository:
1) Make sure the name is the exact same as your R project;
2) Do NOT initialize a README file, .gitignore, or license.


![image](https://user-images.githubusercontent.com/59471339/113391616-627b7d80-93c6-11eb-897a-68eca55e3417.png)





