# GitHudProject
Git Hud Demo

Youtube - How to setup Xcode Projects with Git Hub

1) Download git-2.6.2 
2) Create github account > Add new repo 
3) Create Xcode project > name same as the repo
4) Open Terminal , type following common:

> cd <<local project directory>>
> git init
> git remote add origin http://github.com/jackylcs86/XYZProject.git
> git pull origin master
> ** Enter git mode, press “i” to insert command 
> ** Merge to grab README and gitignore
> ** press “esc” , key in “:x”, press “enter”
// ====== Ways to commit ======//
> git add *
> git commit -m "hello world (added Git Hud Project to github repo)"
//// OR ////
> ls <<to see file list>>
> git add XYZProject XYZProject.xcodeproj
> git commit -m "hello world"
//// OR ////
> Xcode > Source Control > Pull Push