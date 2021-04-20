Hello this is the README!

# GitHub Tutorial (WRIT 155B) 

In this demo you will: 
- Create an online folder in GitHub (your first repository!) 
- Initialize git for the first HTML project we created in WRIT 155B
- Commit and push the project from our local computer to the online repository 
- Create a GitHub page so that we can view our project
- Practice editing the project, committing and pushing the changes

### Required Software 
- Follow [this tutorial](https://www.atlassian.com/git/tutorials/install-git#windows) to install Git on your computer (one time setup) 
- Create an account on [GitHub](https://github.com/)
- Make sure your project files (HTML, CSS, image files etc.) are contained in the **same** folder on your computer 

Follow along with our [video recording]() (Kai still needs to edit) 

### Step 1
In GitHub, create a New repository
- Give the repository any name 
- Make it public 
- DO NOT initalize the repository with a README, gitignore or license 

### Step 2
Find the folder that contains your project files using the File Explorer
- Right click the folder
- Select "New Terminal at Folder" 

### Step 3 
Copy and paste the commands from GitHub to the newly opened Terminal. A brief explanation of what each command does is included below: 
- `git init` - Initializes a Git repository on your local computer 
- `git add *` - Adds all the files in the project folder to Git. The asterisk tells Git to add **all** the files. You cannot also add files one by one with `git add NAMEOFFILE`
- `git commit -m "ANY_RANDOM_MESSAGE"` - "Saves" the current version of your project. You can input a message between the quotation marks to describe what changes you made to your project. 
- `git branch -M main` - Moves git into the a branch called "main." Don't worry too much about branches at this point. 
- `git remote add origin URL_OF_YOUR_REPOSITORY`- Tells Git where to upload the files to. Your URL will be different so make sure to copy and paste from **your GitHub repository** into the Terminal. 
- `git push -u origin main` - Uploads the files from your computer to GitHub! 

### Step 4
Return to GitHub in the browser and **reload the page** to see your uploaded files. 
- Then, click "Settings" 
- Select "Pages" from the menu on the left side of the screen 
- Change "Source" from "None" to "main"
- Save your changes
- Wait 2-3 minutes, then click the URL from the "Pages" tab. You will be redirected to the published version of your website. 

### Updating your project and live website 
After setting up the intial repository the committing and upload process becomes easier. You'll want to add, commit and push your changes every time you make major adjustments to the design/function of your project. Simply: 
- `git add *` to add the files 
- `git commit -m "ANY RANDOM MESSAGE"` to save the files and write a quick description of the changes you made 
- `git push` to upload the altered files from your computer to GitHub 

Your GitHub page (the live website) will update automatically after the files are pushed to the online repository. 

