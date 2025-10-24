# ITE1100_Tutorial4
The purpose of this repository is to demonstrate how Git and GitHub works. This tutorial will guide you to initialize and manage a local Git repository, create, commit, push, and merge changes in Git using branches and pull requests, as well as collaborating with other using GitHub.

How to setup a Git repository:

- Navigate to this site (https://git-scm.com/install/), download and install the latest version of Git for your device.

- Create a new folder on your PC in a location of your choosing. This will be used as your local git repository.

- Open Git Bash. Using the command line interface, navigate to the directory you created using the cd command.

- From there, run the git init command. This will initialize your directory into a git repository.

- Run the git checkout -b (branch_name). This will create a new branch in your repository and switch you over to work in the created branch.

- Create a new text or Python file using a text editor (Notepad), and save the file in your repository.

- Run the git add (file_name) command to add the file to Git. This will let Git recognize your added file that you placed in the folder.

- Commit the new file with a clear message using the command git commit -m (message). This will document any changes with your file.

- Create a new repository on Github and push the local repository to it using the command git remote add origin (Github Repo URL), then the command git push -u origin master.

- Push the new branch to GitHub using the command git push origin (branch_name).

- Choose someone to collaborate with and add them as a Collaborator on your GitHub repository from the Settings tab. 

- Create a Pull Request (PR) and assign your Collaborator as the Reviewer. 

- Wait for your Collaborator to review your request and approve your PR. 

- Once your Collaborator has approved your PR, merge the new branch into the master branch, and delete the created branch.

Collaborators: Andrew Blair & Kimberly Bobb
