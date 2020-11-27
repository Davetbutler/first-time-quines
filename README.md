# First time Quines

Welcome. At Quine our mission is to help early career developers on their journey into the world of software creation. We believe the best way to learn and develop your skills is through contributing to Open Source! In fact we are so convinced of this that we built a tool to help you find where best to contribute. 

Making your first Open Source contribution can be daunting. Here we will walk you through your first contribution step by step: fork -> clone -> branch -> contribute -> commit -> push -> pull request. By the end you will have contributed to this repository! Let's get started. 


## Fork

<img align="left" width="300" height="100" src="" alt="place holder for image"/>
First you need to fork this repo. To do this you simply click the fork button at the top of this page. Now this fork will appear as a repo on your GitHub profile. 


## Clone

<img align="right" width="300" height="150" src="" alt="clone this repository" />
To clone the forked repository onto your computer we have to do two things.

1. Now you have a copy of the repo on your account you can clone it to your local computer. To do this, navigate to the forked repo on your account and click and copy the clone url. It will look something like `https://github.com/your-username/first-time-quines.git`

2. On your machine open up a terminal and `git clone` the repo. 

	```
	git clone https://github.com/your-username/first-time-quines.git
	```
	making sure to use the url you have just copied.


## Branch

You have just copied the fork of the repository you made onto your computer. Now we need to make a branch that you are going to make your contribution on. 

1. Ensure you are in the `first-time-quines` directory. Running the following will ensure you are.
	```
	cd first-time-quines
	```

2. Now you need to create a new branch. The `git checkout` command will allow you to do this. The `-b` is used to create a new branch, you can call it what you want - generally it is good practice to give it a descriptive name `my-new-branch-that-does-something`

	```
	git checkout -b my-new-branch-that-does-something
	```


## Contribute 

Now it is time for the fun part - making your contribution.

TODO: think of cool way for people to make contributions. The baseline is something like adding your name to a list.


## Commit

Well done on making your contributions, now we need to let everyone else see them. Committing is a two stage process:

1. First we need to add the changed files, to do this we use the `git add` command, we must add all the files we have contributed to. TODO: depending on the contribution we suggest is made we get them to add the corresponding files.
	```
	git add ...
	```
2. Now we need to commit those changes using the `git commit` command, here we use the `-m` flag to add a message to the commit, it is good practice write a concise but descriptive message to help others understand what you have done:

	```
	git commit -m "your commit message"
	```


## Push 

Now we are ready to push the committed changes to GitHub using the `git push` command. We must tell GitHub which branch to push, by adding the branch name we are ensuring we are pushing to the corresponding remote branch:

```
git push origin <add-your-branch-name>
```

If you go to the branch on your GitHub account you will now be able to see the commit you have just made - remember to look on the correct branch, there will be no changes on the master branch.

## Pull request

Now the changes have been made on your GitHub account it is time to make a pull request and submit it to the `first-time-quines` repository. 

To do this you can go to the branch on your GitHub account and click pull request. You will be able to leave a comment before submitting. It is good practice to leave a short comment to help the maintainer who will be reviewing and accepting the pull request - just tell them what you have done. TODO: give example comment based on what we get them to contribute to.

Once you have done this submit the pull request

<img   src="" alt="place holder for image"/>

Now submit the pull request.


## Over to us

Now you have submitted your pull request you can sit back and relax and wait until it is 
accepted and merged into the main branch of this project - but don't worry we will do this as soon as possible! You will recieve an email when it is done.  

