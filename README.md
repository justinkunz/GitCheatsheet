# Git Cheatsheet

## Adding Projects/Homework Assignments to Github

1. Create a dedicated directory for your project on your computer.
   _(Remember, you can use the `mkdir` command to make a new directory, and `cd` to navigate to it)_
2. Copy all your project-related files or stater code into this folder
   _(Remember to maintain the same folder structure. For homeworks, starter code lives within the `Develop` folder)_
3. Inside your new project folder, run the following commands:

```
git init
git add .
git commit -m "initial commit"
```

4. Create a new repo on Github
   _(You should have a seperate repo for each project or homework assignment)_

5. Run the following commands in your project folder

```
git remote add origin <url to your new Git Repo>
git branch -M main
git push -u origin main
```

## Updating an Existing Repo

To update an existing repo with changes you've made, navigate to that folder and run the following commands:

```
git add .
git commit -m "<your commit message here>"
git push
```
