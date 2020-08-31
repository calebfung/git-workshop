# Git and Gitflow Workshop

This repository has been created to build a basic knowledge of git and gitflow. 

## Getting Started

### Workshop Dependencies

To follow along with the workshop, you'll need the following:

#### A Git client

GitHub Desktop can be downloaded from [their website](https://desktop.github.com/).

If'd you'd prefer a terminal environment, git can be downloaded from [their website](https://git-scm.com/downloads).

#### A GitHub Account

To properly handle pull requests, you'll want a GitHub account. [Sign up here](https://github.com/join).

#### NodeJS

The workshop was built using a React application, meaning you'll need NodeJS installed. Download NodeJS [here](https://nodejs.org/en/download/)

### Getting the application

#### Forking the original repository

From the [original repository](https://github.com/kulinacs/git-workshop), click the `Fork` button to create your own copy.

#### Clone the forked repository

From your git client, find the forked repository and clone it to begin working on it.

### Running the application

Open a terminal in the folder that you cloned the repository to. In it, run
    
    npm install
    
to pull in all needed dependencies. Then run

    npm start
    
to run the application. It should be available on `localhost:3000` in your browser.

## Getting started with Git

### Handle your first PR

* Open a pull request for the `feature/add-counters` branch to the `develop` branch via the Pull requests tab.
* Review the changes that will be made.
* Merge the pull request into the `develop` branch.

### Create your first feature

* Update the `develop` branch locally to include your new changes
* Create a new branch `feature/update-title`
* Edit the title `Counter` in `components/NavBar.js` to whatever you would like and save your changes
* Create a new commit describing your changes
* Push the new branch to the remote
* Follow the steps you did before to create a pull request to develop

### Handle your first merge conflict

* Open a pull request for the `feature/delete-counter` branch to the `develop` branch via the Pull requests tab.
* Notice you have a merge conflict, which means you can't auto merge
* On your local machine, merge `develop` into `feature/delete-counter` and handle the changes
* Push the changes to `feature/delete-counter`
* Merge your pull request

### Release your software

* Follow the instructions you've done before, but this time merge `develop` to `master`
