# Welcome to the home of the China Siqing Social Class Dataset (CSSCD) series codebase

Current owner-collaborators are:
  - Matthew Noellert, University of Iowa
  - Li Xiangning, HKUST

## Organization
/core contains the .do files that are used to generate the dataset. These files are collaboratively managed. 
/analysis contains the .do files of individual research projects and papers. These files are mostly managed individually. 

The raw data is stored on a shared HKUST OneDrive folder.

## Example workflows

### 1. Getting started from scratch
  - Go to https://git-scm.com/downloads. Download and install git, the version control system being used by this codebase.
  - Go to https://desktop.github.com/. Download and install GitHub Desktop, a program that makes using git easier for us.
  - Go to https://github.com/noellert/CSSCD and clone the repository (base project directory containing all the codebase files) to your local pc: click on the green "Clone or download" button, then click on "Open in Desktop", and choose a good location to keep your version of the repository.
  - Now you have a local copy of the project (repository). From now on you will work on your own local copies of all the files, and then sync them back and forth with the remote online repository. The remote repository is the communal home of all the files. At any given time, it contains a "master" version of all files, together with different versions of the files that individual collaborators are working on, which exist in "branches" off of the master. These branches can be merged back into the master to update the master version at any given time, or continue to develop independently. 

### 2. Simple revisions/updates
  - Edit the .do file on your local machine, as you normally would.
  - Open GitHub Desktop. It will automatically display all the changes you have made to all files in your local /CSSCD respository since the last time you synced.
  - Click on "Fetch origin" tab to sync with the remote repository and ensure your local files are up to date.
  - In the lower left panel, add a brief summary and description of the changes you are making, e.g. "Update text processing_generated.do", "add new conditions for monthly incomes". Then click the blue "Commit to master" button. This saves your changes to the master version oyour version (branch) of the codebase, without changing the master version on github.com.

### 2. Editing /core files
  - Edit the .do file on your local machine, as you normally would.
  - Open GitHub Desktop. It will automatically display all the changes you have made to all files in your local /CSSCD respository since the last time you synced.
  - Click on "Fetch origin" tab to sync with the remote repository and ensure your local files are up to date.
  - Click on the "Current branch" tab, and type in a name for your version, then click "new branch". E.g. if I am editing the income variable coding in the text processing .do file, I would call my branch something like, "text processing income code" (You do not need to include your name, because GitHub keeps track of who does what). DO NOT use the master branch.
  - In the lower left panel, add a brief summary and description of the changes you are making, e.g. "add new conditions for monthly incomes". Then click the blue "Commit to [branch name]" button. This saves your changes to your version (branch) of the codebase, without changing the master version on github.com.
  - Optional: If you would like to share your changes with your collaborators or just sync across multiple PCs, at this point you can either publish your new branch, or "push" your changes on an existing branch to the "origin" remote repository. In both cases, this updates the information on the remote repository, i.e. adds your local branch to it. NOTE: At this point your changes still exist as an independent version, all this step does is make them visible to your collaborators.
  - Once you have finished your current task (in this example revising the text processing income code) and made sure it runs ok in Stata, you can merge your changes (branch) into the master version. To accomplish this, in GitHub desktop go to Branch\Create pull request (ctrl-R), which will open up the github.com repository and take you to "Open a pull request". (If you haven't published or pushed your branch to the remote repository, you will prompted to do so now.) Here you can review conflicts, if any, add more description of what your changes do, add people who you want to review or check your changes, etc. When you are ready, click the green "Create pull request" button. If github can handle the merge itself, then you can click the new green "Merge pull request button", then "Confirm merge". Now you have merged your changes into the master version of the file(s) (i.e. updated the master with your changes) and your branch is redundant, so you can delete your branch with the "Delete branch" button that should appear once the merge is successful.
  - Repeat next time you start a new task.

### 3. Editing /analysis files