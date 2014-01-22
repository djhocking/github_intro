# Introduction to Using GitHub

![Octocat icon](file:/Users/Dan/Pictures/Octocat/Octocat.png =150x)

## Definitions
<br>

## Directions

*This assumes you have set up git on your local machine. If you have not yet done so, you can find step-by-step instructions at <https://help.github.com/articles/set-up-git>*

### Initial Repository Setup

#### *OPTION 1: If you do not yet have a folder or files on your local machine*

1. Log into github.com
2. Create new repository (+ symbol in upper right)
3. Add the name of the repository, a README.md file (check the box "Initialize this repository with a README "), a .gitignore file (optional: allows you to have things that are not tracked, can be added later), a license, and a brief description of the repository
4. Decide if the repository will be public (free) or private (pay service)
5.  Click "Create Repository"
6.  Highlight and copy the the **HTTPS** clone URL link on the bottom of the right-hand column
7.  Open your command line interface (Terminal app on Mac OS)
8.  cd to your desired directory where you want to add (clone) your new folder
9.  type `git clone https://URL-Copied-From-GitHub` (if you have the finder window open you can see new folder appear)
10.  Now you can populate this local folder and push changes to the GitHub repository

#### *OPTION 2: If you already have a folder on your computer that you want to create a GitHub repository for*

1. Log into github.com
2. Create new repository (+ symbol in upper right)
3. Add the name of the repository, **DO NOT** check the box "Initialize this repository with a README ") or add a .gitignore file. It should be okay to add license information and a brief description of the repository



## Push changes to folder to GitHub

1. Check what files have been changes with `git status` command
2. Add (stage) the files you want to change in the next commit with the `git add` command or use `git add .` to add all
3. Commit to the changes that were staged using `git commit -m "Message about why you made the changes"`. Now it has saved your changes on your local machine
4. Push the changes on your local remote repository to GitHub using `git push origin master`. This means you are pushing your local remote repository named origin to the GitHub branch named master. You can use different local remote names and you can also work in and push to different branches on GitHub. Now if you check on GitHub.com you will find your files in the master branch updated to match your local files.















