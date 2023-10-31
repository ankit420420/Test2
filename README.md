# Test1
This is Test1 repositoryfgfhgcvxc
first commit

# *****************USING GITHUB MANUALLY*****************

# To upload projects on GITHUB
    a.	Create GITHUB repository
    b.	Create README.md file in local project
    c.	Create .gitignore file in local project and add the files to ignore uploading to GITHUB
    d.	Uploading project to GITHUB


# Create GIT repository in GITHUB
    Step 1: Click on NEW in Github homepage
    Step2: It opens up a page to enter git repository details. 
        •	Enter the repository name
        •	Add repository description
        •	Select repository as Public or Private. For now set it as public (Public repository can be seen by anyone. Private 
            repository will be accessible when permission is granted)
        •	Select checkbox for “Add readme file”
        •	Select Node for “Add .gotignore”
        •	Select none for “License”
    Step3: Click on Create Repository

    It creates a repository with initial commit with
        •	Branch name as main
        •	README.md
        •	.gitignore files and

# Notes
    .gitignore file contains
        a)	dist
        b)	node_modules
        c)	*.log
        d)	.env


# Create README.md file in project
    Create a README.md fle in project root directory to add notes related to project, useful at later stages of projects and others working on the project

# Create .gitignore file in project and add the files to ignore uploading to GITHUB
    Create a .gitignore file in project root directory and add the data of .gitignore file created when repository is created

# Uploading project to GITHUB
    To upload project to github follow the following steps:
        •	git init
        •	git add –A
        •	git commit –m <”commit message”>
        •	git branch –m main     
                      by default local branch is create with name as “master”. To change name use the above command
        •	git remote add origin <github repository url>
        •	git push -u -f origin main                      (main or whatever is your branch name)
                         (-u: This switch makes the remote GitHub repo the default for your existing project.                     
                         -f: This switch forces Git to overwrite any files that already exist on GitHub with your existing 
                            project’s files.)

    This pushes the current project on github

-----------------------------------------------------------------------------------------------------------------------------

# To update a project on GITHUB
    After making changes in project follow these steps:
        •	git add –A
        •	git commit –m <”commit message”>
        •	git pull
    
    If updated code is pushed from repository then follow steps 1,2,3 agin is same order, else move to next step
        
        •	git push

    This pushes the project changes on github
    
-----------------------------------------------------------------------------------------------------------------------------

# To clone a GITHUB repository
    •	Open the project on GTIHUB
    •	Click on Code button
    •	Copy the git url
    •	Open the terminal in the project’s root directory, then follow the following commands
    •	npm i              (as node_modules folder is not uploaded on github so it installs that folder in project)

-----------------------------------------------------------------------------------------------------------------------------

# To add remote to project
    •	git remote add origin <github repository url>

-----------------------------------------------------------------------------------------------------------------------------

# To remove remote from project
    •	git remote remove origin

-----------------------------------------------------------------------------------------------------------------------------

# To push after removing and adding back the remote origin                            
    •	git push --set-upstream origin main


==========================================================================



# *****************USING GITHUB THROUGH VSCODE*****************

# Way 1
# To upload a project on GITHUB by creating repository manually
    a.	Create GITHUB repository
    b.	Create README.md file in local project
    c.	Create .gitignore file in local project and add the files to ignore uploading to GITHUB
    d.	Uploading project to GITHUB


# Create GIT repository in GITHUB
    Step 1: Click on NEW in Github homepage
    Step2: It opens up a page to enter git repository details. 
        •	Enter the repository name
        •	Add repository description
        •	Select repository as Public or Private. For now set it as public (Public repository can be seen by anyone. Private 
            repository will be accessible when permission is granted)
        •	Select checkbox for “Add readme file”
        •	Select Node for “Add .gotignore”
        •	Select none for “License”
    Step3: Click on Create Repository

    It creates a repository with initial commit with
        •	Branch name as main
        •	README.md
        •	.gitignore files and

# Notes
    .gitignore file contains
        a)	dist
        b)	node_modules
        c)	*.log
        d)	.env


# Create README.md file in project
    Create a README.md fle in project root directory to add notes related to project, useful at later stages of projects and others working on the project

# Create .gitignore file in project and add the files to ignore uploading to GITHUB
    Create a .gitignore file in project root directory and add the data of .gitignore file created when repository is created

# Uploading project to GITHUB
    Step 1: Go to file->Open folder and select the project folder and open it
    Step 2: Click on Source Control option or Press Ctrl+Shft+G to open a left panel and click on initialize repository
    Step 3: Click on Source Control->3 dots beside Source Control label-> Remote->Add Remote      or       Press Ctrl+Shft+P and 
            select GIT:Add remote
    Step 4: Then select Add remote from GITHUB. It will open browser to Authenticate login to GITHUB from VSCode
    Step 5: Select from the list of all the existing repositories or type <username/repository-name>
    Step 6: Stage all the changes form the left panel by clicking on the + sign
    Step 7: Click on Commit button to commit all the changes. If will ask to enter the commit message. Enter the message and 
            submit on top right corner
    Step 8: Click on Publish branch in left panel

    This pushes the current project on github

# Note
    If things doesn’t seems to work then close and reopen VSCode



# Way 2
# To upload a project on GITHUB without creating repository manually
    In this case no need to create a GITHUB repository manually beforehand. Just follow the below steps:
        a.	Create README.md file in local project
        b.	Create .gitignore file in local project and add the files to ignore uploading to GITHUB
        c.	Uploading project to GITHUB

# Create README.md file in project
    Create a README.md file in project root directory to add notes related to project, useful at later stages of projects and others working on the project

# Create .gitignore file in project and add the files to ignore uploading to GITHUB
    Create a .gitignore file in project root directory and add the data of .gitignore file created when repository is created

# Uploading project to GITHUB
    Step 1: Go to file->Open folder and select the project folder and open it
    Step 2: Click on Source Control option or Press Ctrl+Shft+G to open a left panel and click on Publish to GITHUB
    Step 3: Dialog box opens with the name of the repository prepopulated. You can rename it and press enter. It
    Step 4: It shows option to publish it as private or public. Select any option.
    Step 5: Then click on Publish

    It creates a repository with initial commit with
        •	Branch name as main

# Note
    If things doesn’t seems to work then close and reopen VSCode

-----------------------------------------------------------------------------------------------------------------------------

# To update a project on GITHUB from VSCode
    a.	Click on Source Control option or Press Ctrl+Shft+G to open a left panel
    b.	Stage all the changes from the left panel by clicking on the + sign
    c.	Click on Commit button to commit all the changes. If will ask to enter the commit message. Enter the message and submit 
        on top right corner
    d.	Click on Publish branch in left panel

    This pushes the project changes on github

-----------------------------------------------------------------------------------------------------------------------------

# To clone a GITHUB repository from VSCode
    a.	Click on Source Control option or Press Ctrl+Shft+G to open a left panel and click on Clone repository (no folder should 
        be open at this point in VSCode)
                                              Or
        Press Ctrl+Shft+P and type Gitclone  (If any folder or project is open in VSCode)
    b.	Click on Clone from GITHUB
    c.	Select from the list of repositories to clone
    d.	Select the destination folder to clone the repository

-----------------------------------------------------------------------------------------------------------------------------

# To add remote from VSCode
    a.	Click on Source Control option or Press Ctrl+Shft+G to open a left panel
    b.	Click on 3 dots beside Source Control label
    c.	Click on Remote->Add Remote


-----------------------------------------------------------------------------------------------------------------------------

# To remove remote from VSCode
    a.	Click on Source Control option or Press Ctrl+Shft+G to open a left panel
    b.	Click on 3 dots beside Source Control label
    c.	Click on Remote->Remove Remote

-----------------------------------------------------------------------------------------------------------------------------

# To push after removing and adding back the remote origin from VSCode                       

    a.	Click on Source Control option or Press Ctrl+Shft+G to open a left panel
    b.	Stage all the changes from the left panel by clicking on the + sign
    c.	Click on Commit button to commit all the changes. If will ask to enter the commit message. Enter the message and submit 
        on top right corner
    d.	Click on Publish branch in left panel

    This pushes the project changes on github

==========================================================================