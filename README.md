Documentation
=============

This repository will contain markdown documentation of each repository and their systems as well as workflow instructions

See the [wiki](https://github.com/NeverGoneBot/NeverGoneBotDocumentation/wiki) for component specific info 

###### Repositories

1. [iOS](https://github.com/NeverGoneBot/NeverGoneBotIOS)
2. [Android](https://github.com/NeverGoneBot/NeverGoneBotAndroid)
3. [Web](https://github.com/NeverGoneBot/NeverGoneBotWeb)
4. [Arduino](https://github.com/NeverGoneBot/NeverGoneBotArduino)
5. [Server](https://github.com/NeverGoneBot/NeverGoneBotServer)

###### Git Workflow

The git workflow is simple and consists of the following rules:

  1. Branches will be made for FEATURES or BUG FIXES and not specific developers
  2. If you think of a feature or bug fix, simply create a "New Issue" and title it with the feature or bug fix (i.e. "Video Streaming Crash" or "Login")
  2. If you are creating a branch, name it like this: "<Dev Name>/<IS-Issue #" (i.e. for the Test issue in this repository, I would do "Shreyas/1")
  3. If you another developer is working on a feature and you would like to add something, create a new branch off of that feature branch, DO NOT create a branch of the master branch (unless the feature has already been merged in)
  4. Once you have thorougly TESTED and reviewed your own code, create a pull request towards the branch that your branch originated from. So, if you created a branch from master to add a new feature, submit a pull request to master. If you created a branch from another branch submit a pull request to that branch.
  5. This code will be reviewed by at least two others and if it's good, the pull request will be merged into the parent branch. If not, it will be rejected and a reason will be given. 
  6. Once a pull request is merged, DELETE the branch.



Top-Level Data Flow Diagram

![](https://github.com/NeverGoneBot/NeverGoneBotDocumentation/blob/master/Data%20Flow.png)
