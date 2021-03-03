![giphy](https://user-images.githubusercontent.com/34379958/109859738-16f57880-7c3c-11eb-919e-aa318dbd9170.gif)

Project name: google-clone
Description: this project is intended for those who are interested in learning HTML, CSS and Git.
Level: beginners. 

STEPS TO FOLLOW TO MAKE A PR
* In a project in which we are not collaborators:
    1. Create a fork of the project you want to collaborate on.
    2. Clone the repository.
    3. Create a remote.
    4. Perform a pull of the original repository.
    5. Create a new branch.
    6. Make the changes and generate a commit.
    7. Perform a push.
    8. Pull Request (PR).

* In a project in which we are collaborators:
    1. Clone the repository.
    2. Perform a pull of the original repository.
    3. Create a new branch.
    4. Make the changes and generate a commit.
    5. Perform a push.
    6. Pull Request (PR).

Detailed steps: 
1. Create a fork of the project: at the top right of the page is the "fork" button, click on it. This creates an instance of the entire repository with all its history, allowing us to make the changes we want without affecting the original version. 
2. Clone the repository: now that the repository is already in your account, you must clone it to work locally. To clone it, click on the "Code" button and copy the link.
Open the terminal and run the following command "git clone [link]". This will clone the repository locally. Then run the following command "git cd [repository name]" to enter the folder where the project you just cloned is located. 
3. Create a remote: in order to collaborate, you need to manage remote repositories. These are versions of your project that are hosted on the internet.
To see which remotes you have configured run the command "git remote -v". And to create a new remote run the command "git remote add [name] [url]". In this case, the url that you must put is the one of the original repository where you are going to collaborate. Make sure that the name is according to the project, you will need it in the next step.
4. Perform a pull of the original repository: maybe not everything is updated, so we must make sure we have the latest version of the project to avoid problems. Execute the command "git pull [remote name] master".
5. Create a new branch: now that you have everything updated, you can create a branch to make the changes you want to make. Run the command "git checkout -b [branch name]" to create a new branch and switch to it in one step. 
6. Make the changes and generate a commit: once you have made the modifications you should check the status, add those changes and commit them. Execute the commands:
    * "git status" to know the status of the files. If they are shown in red it is because they are not staged.
    * git add [filename]": change the status of the files to staged. If we then run "git status" we can see that the files are green. 
    We can also use the command "git add ." to add all changes in one step.
    * git commit -m "[commit name]": commit the changes you made so you can upload them.
7. Perform a push: once the changes are ready, you upload it so you can make a pull request. Execute the command "git push origin [branch name]". The result of this will be a list with information, including a link that directs you to the page where you can do the PR.
8. Pull Request (PR): once you have entered the link, you only have to complete the pull request with a title and a description and click on the button to request it. Then you wait for them to accept or reject your changes or contributions in the repository. 
