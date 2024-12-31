# codecatalyst-learning
This work with the project Hostel Attendance System .


--GIT LEARNING

 1. Configure Git Bash with your username, email, password, etc
    1. Set Your Git Name to Match GitHub(Use the same name as your GitHub profile )
    git config --global user.name "Your GitHub Name" 
    
    2. Set Your Git Email to Match GitHub(Set the email associated with your GitHub account)
    git config --global user.email  "your.github.email@example.com"

2. Create a repository named codecatalyst-learning on your system
   1. Create a Local Repository:  (In vs code)
    mkdir codecatalyst-learning
    cd codecatalyst-learning
    git init
    

3.  Push your codecatalyst-learning repository to GitHub
    1. Connect to a Remote Repository (Optional): (In GitHub)
     git remote add origin <repository-URL (github repository link )>
     git push -u origin main
    
4. Add a sample file (e.g., README.md) to your repository and stage it using git add.
    1. Add a File:
     echo "readme file" > README.md 
     git add README.md 
     git commit -m "Initial commit“

5. Make changes to the file and use git status to view staged changes.
    git status 

6. Commit the staged changes with a meaningful commit message.
    git commit -m "Newly commited change“

7. Push your committed changes to the GitHub repository.
    git push origin main

8. Create a branch named "secondary-branch"
    1. git branch "secondary-branch"

9. Switch to the "secondary-branch" branch
    1. git checkout "secondary-branch"
    2. git add .
    3. git commit -m "New branch"
    4. git push origin "secondary-branch"  (Automatically adds a branch in github)

on secondary branch 
