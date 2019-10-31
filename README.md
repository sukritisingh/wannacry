# WANNACRY
Analyzing wannacry.exe

# Why GITHUB
We can create a shared project but that requires a server and we dont have it bois.

# Sharing projects
Let's try to do what professor did in class where we assign names to functions and variables we can make sense of, we can also add comments in Ghidra so this can be something we can use. 

To share a project, first, save your changes and then close the code browser window. In the projects window, select File>Archive Current Project. This will create a .gar file which can be then used to restore by selecting File>Restore Project. Upload the .gar file.

You will need to fork the repository from the github UI. Go to https://github.com/Pankul94/wannacry and click on fork.
After forking you will get .gar file that I have uploaded, restore the project in your machine and start from there. Once you have made changes, save and archive(mentioned above).Commit and push the archieved .gar file to your forked repo. Create the pull request and I will merge it which can then be used by others as well.

Commands that you will need:<br>
To add your .gar file into a tracked files: git add . <br><br>
To commit: git commit -m 'Your message. Try to be informative, if you have changed a function or analysed a part please make sure you                               write it here so that someone else does not spend time on it'<br><br>
To Push: git push origin master<br><br>
To Pull: git pull upstream master --Pull will give you the new file that was the latest that anyone of us has worked on.<br><br>

After this go to your forked repo and create a pull request, you can add comments in the PR as well.

