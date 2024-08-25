# Git Assignment - amirfarimani

a. What is an issue?
Issues are used to track todos, bugs, feature requests, and more. As issues are created, they’ll appear here in a searchable and filterable list.

b. What is a pull request?
Pull requests help you collaborate on code with other people. As pull requests are created, they’ll appear here in a searchable and filterable list.
c. Describe the steps to open a pull request?
Option 1: On GitHub (Directly on the Website)
Create a Branch:

On GitHub, navigate to the repository.
Click on the branch dropdown and select "New branch."
Name your branch and create it.
Make Changes:

Edit the files directly on GitHub within your new branch.
Commit the changes with a descriptive commit message.
Open a Pull Request:

Go to the "Pull requests" tab.
Click "New pull request."
Select your branch as the source and main (or another target branch) as the destination.
Add a title and description, then click "Create pull request."

Option 2: On Local Machine
-Clone the Repository:
git clone https://github.com/owner/repository-name.git


-Navigate to the repository directory:
cd repository-name
-Create a new branch for your changes: 
git checkout -b my-feature-branch

-Edit files on your local machine.
-Stage and commit your changes:
git add .
git commit -m "Description of the changes"
-Push the Branch to GitHub:
Push your branch to the remote repository:
git push origin my-feature-branch
-On GitHub, navigate to the repository.
-Go to the "Pull requests" tab and click "New pull request."
-Select your branch as the source and main (or another target branch) as the destination.
-Add a title and description, then click "Create pull request."

d. Describe the steps to add a collaborator to a repository (share write permissions)

Go to Repository Settings:

Navigate to the repository on GitHub.
Click on the "Settings" tab.
Manage Access:

In the "Settings" tab, find the "Manage access" section.
Click the "Invite a collaborator" button.
Invite a Collaborator:

Enter the GitHub username or email address of the person you want to add.
Select the permission level (e.g., Write, Read).
Send the invitation.
Collaborator Accepts:

The invited collaborator will receive an email invitation.
Once they accept, they will have the permissions you granted (e.g., write access).

e. What is the difference between git and GitHub?

Git is a distributed version control system that helps developers track changes in source code during software development. It allows multiple developers to work on a project simultaneously, maintaining a history of changes and enabling features like branching, merging, and reverting changes.

GitHub is a web-based platform that hosts Git repositories. It provides a collaborative environment for developers, allowing them to store, share, and manage their Git repositories, as well as tools for issue tracking, code review, and project management. Essentially, GitHub leverages Git for version control while adding a web interface and additional features.

f. What does git diff do?

he git diff command shows the differences between various Git data sources, such as the working directory, staging area, and committed versions of files. It highlights changes made in terms of added, modified, or deleted lines of code. 

g. What is the main branch?

the primary branch in a Git repository. It contains the most stable and production-ready version of the project. All new features and fixes are typically merged into this branch after they've been tested and reviewed in other branches.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

No, you generally shouldn't push changes directly to the main branch after the initial commit, especially in a collaborative project. Instead, it's best practice to:

Create a New Branch for your changes.
Make and Commit Your Changes on this branch.
Open a Pull Request to merge your branch into the main branch.