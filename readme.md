# Welcome to the home of the China Siqing Social Class Dataset (CSSCD) series codebase.

Current owner-collaborators are:
  - Matthew Noellert, University of Iowa
  - Li Xiangning, HKUST

## Organization
/core contains the .do files that are used to generate the dataset.  
/analysis contains the .do files of individual research projects and papers.

The raw data is stored on a shared HKUST OneDrive folder.

## Example workflows

### 1. Getting started from scratch.
  - Go to https://git-scm.com/downloads. Download and install git, the version control system being used by this codebase.
  - Go to https://desktop.github.com/. Download and install GitHub Desktop, a program that makes using git easier for us.
  - Go to https://github.com/noellert/CSSCD and clone the repository (base directory of our codebase files) to your local pc: click on the green "Clone or download" button, then click on "Open in Desktop", and choose a good location to keep your version of the repository.
  - Now you have a local copy of the codebase (repository). From now on you will work on your own local copies of all the files, and then sync them back and forth with the GitHub online repository. The online repository is the communal home of all the files. At any given time, it contains a "master" version of all files, together with different versions of the files that individual collaborators are working on, which exist in "branches" off of the master. These branches can be merged back into the master to update the master version at any given time, or continue to develop independently. 

### 2. Editing /core files.
  - Edit the .do file on your local machine, as you normally would.
  - Open GitHub Desktop. It will automatically display all the changes you have made to all files in /CSSCD since the last time you synced.
  - Click on the "Current branch" tab, and type in a name for your version, then click "new branch". E.g. if I am editing the income variable coding in the text processing .do file, I would call my branch, "text processing income code" (You do not need to include your name, because GitHub keeps track of who does what). DO NOT use the master branch.
  - In the lower left panel, add a brief summary and description of the changes you are making, e.g. "add new conditions for monthly incomes". Then click the blue "Commit to [branch name]" button. This saves your changes to your version (branch) of the codebase, without changing the master version on github.com.
  - Now you can either publish your new branch, or "push" your changes on an existing branch to the "origin" github.com repository. In both cases, this updates the information on the github.com repository, i.e. shares your changes with whoever else is collaborating on the repository. NOTE: At this point your changes still exist as an independent version, all you have done now is made them visible to your collaborators.
  - Once you have finished your current task (in this example revising the text processing income code) and made sure it runs ok in Stata, you can merge your changes (branch) into the master version. To accomplish this, in GitHub desktop go to Branch\Create pull request (ctrl-R), which will open up the github.com repository and take you to "Open a pull request". Here you can review conflicts, if any, add more description of what your changes do, add people who you want to review or check your changes, etc. When you are ready, click the green "Create pull request" button. If github can handle the merge itself, then you can click the new green "Merge pull request button", then "Confirm merge". Now you have merged your changes into the master version of the file(s), and your branch is redundant, so you can delete your branch with the "Delete branch" button that should appear once the merge is successful.
  - Regularly click the "Fetch origin" tab in GitHub Desktop. This syncs your local files with the online files and ensures you have the most recent versions.

