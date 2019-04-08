Welcome to the home of the China Siqing Social Class Dataset (CSSCD) series codebase. Current owner-collaborators are:
  - Matthew Noellert, University of Iowa
  - Li Xiangning, HKUST

Organization:
/core contains the .do files that are used to generate the dataset.
/analysis contains the .do files of individual research projects and papers.

The raw data is stored on a shared HKUST OneDrive folder, /Xiangning LI - CSSCD.

Example workflows:

1. Getting started from scratch.
  -  Go to https://git-scm.com/downloads. Download and install git, the version control system being used by this codebase.
  - Go to https://desktop.github.com/. Download and install GitHub Desktop, a program that makes using git easier for us.
  - Go to https://github.com/noellert/CSSCD and clone the repository (base directory of our codebase files) to your local machine: click on the green "Clone or download" button, then click on "Open in Desktop".
  - Now you have a local copy of the codebase (repository). From now on you will work on your own local copies of all the files, and then sync them back and forth with the GitHub online repository. The online repository will always represent the "master" version of all files. Your local versions will represent your own modified versions of the files, until your changes are synced with the master. 

2. Editing /core files.
  - Edit the .do file on your local machine, as you normally would.
  - Open GitHub Desktop. It will automatically display all the changes you have made to all files in /CSSCD since the last time you synced.
  - Click on the "Current branch" tab, and type in a name for your version, then click "new branch". E.g. if I am editing the income variable coding in the text processing .do file, I would call my branch, "text processing income code".
  - In the lower left panel, add a brief summary and description of the changes you are making, e.g. "add new conditions for monthly incomes". Then click the blue "Commit to [branch name]" button. This saves your changes to your version (branch) of the codebase, without changing the master version on github.com.
  - Now you can either publish your new branch, or "push" your changes on an existing branch to the "origin" github.com repository. In both cases, this updates the information on the github.com repository, i.e. shares your changes with whoever else is collaborating on the repository. NOTE: At this point your changes still exist as an independent version.
  - 
