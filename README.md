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

=> ABOUT THIS PROJECT :

Do you realize that the only functionality of a web application that the user directly interacts with is through the web page? Implement it poorly and, to the user, the server-side becomes irrelevant! Today’s user expects a lot out of the web page: it has to load fast, expose the desired service, and be comfortable to view on all devices: from a desktop computers to tablets and mobile phones.

In this PROJECT, you will learn the basic tools that every web page coder needs to know. We will start from the ground up by learning how to implement modern web pages with HTML and CSS. We will then advance to learning how to code our pages such that its components rearrange and resize themselves automatically based on the size of the user’s screen. You’ll be able to code up a web page that will be just as useful on a mobile phone as on a desktop computer. No “pinch and zoom” required! 

In this project, you’ll learn how to keep track of the different versions of your code and configuration files using a popular version control system (VCS) called Git. We'll also go through how to setup an account with a service called GitHub so that you can create your very own remote repositories to store your code and configuration. 

Throughout this project, you'll learn about Git's core functionality so you can understand how and why it’s used in organizations. We’ll look into both basic and more advanced features, like branches and merging. We'll demonstrate how having a working knowledge of a VCS like Git can be a lifesaver in emergency situations or when debugging. And then we'll explore how to use a VCS to work with others through remote repositories, like the ones provided by GitHub.

By the end of this course, you'll be able to store your code's history in Git and collaborate with others in GitHub, where you’ll also start creating your own portfolio! 