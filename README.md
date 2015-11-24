# GitHudProject
Git Hud Demo

Youtube - How to setup Xcode Projects with Git Hub  
https://www.youtube.com/watch?v=2U_84-vg8OE  

1) Download git-2.6.2  
2) Create github account > Add new repo  
3) Create Xcode project > name same as the repo  
4) Open Terminal, cd <<local project directory>>  
5) git init  
6) git remote add origin http://github.com/jackylcs86/XYZProject.git  
7) git pull origin master  
8) ** Enter git mode, press “i” to insert command  
9) ** Merge to grab README and gitignore  
10) ** press “esc” , key in “:x”, press “enter”  

// ====== Ways to commit ======//  
1) git add *  
2) git commit -m "hello world (added Git Hud Project to github repo)"  
//// OR ////  
1) ls <<to see file list>>  
2) git add XYZProject XYZProject.xcodeproj  
3) git commit -m "hello world"  
//// OR ////  
1) Xcode > Source Control > Pull Push  
