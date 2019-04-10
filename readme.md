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
  1. Go to https://git-scm.com/downloads. Download and install git, the version control system being used by this codebase.
  2. Go to https://desktop.github.com/. Download and install GitHub Desktop, a program that makes using git easier for us.
  3. Go to https://github.com/noellert/CSSCD and clone the repository (base project directory containing all the codebase files) to your local pc: click on the green "Clone or download" button, then click on "Open in Desktop", and choose a good location to keep your version of the repository.
  4. Now you have a local copy of the project (repository). From now on you will work on your own local copies of all the files, and then sync them back and forth with the remote online repository. The remote repository is the communal home of all the files. At any given time, it contains a "master" version of all files, together with different versions of the files that individual collaborators are working on, which exist in "branches" off of the master. These branches can be merged back into the master to update the master version at any given time, or continue to develop independently. 

### 2. Simple .do file revisions/updates
  1. Edit the .do file on your local machine, as you normally would.
  2. Open GitHub Desktop. It will automatically display all the changes you have made to all files in your local /CSSCD respository since the last time you synced.
  3. Click on "Fetch origin" tab to sync with the remote repository and ensure your local files are up to date.
  4. In the lower left panel, add a brief summary and description of the changes you are making, e.g. "Update text processing_generated.do", "add new conditions for monthly incomes". Then click the blue "Commit to master" button. "Commit" means create a save point. This saves your changes to the master version of the file(s) on your pc. To update the shared master version on the remote repository, click the blue "Push to origin" button.
  5. Now the next time someone else syncs with the remote repository, they will get the updated master version with your new changes. If multiple people make changes at the same time, or if local and remote versions come into conflict, then GitHub will prompt you to resolve them.

### 3. Complicated .do file revisions/updates
  1. Follow steps 1-3 for simple revisions.
  2. Click on the "Current branch" tab, and type in a name for your version, then click "new branch". E.g. if I am overhauling the income variable coding in the text processing .do file, I would call my branch something like, "income code overhaul" (You do not need to include your name, because GitHub keeps track of who does what). DO NOT use the master branch.
  3. In the lower left panel, add a brief summary and description of the changes you are making, e.g. "Update text processing_generated.do" "add new conditions for monthly incomes". Then click the blue "Commit to [branch name]" button. This creates an independent, local version (branch) of the file(s), that now exists parallel with the master version (default branch).
  4. Optional: If you are still working on your task, but would like to share your changes with your collaborators or just sync across multiple PCs, at this point you can either publish your new branch, or "push" your changes on an existing branch to the "origin" remote repository. In both cases, this updates the information on the remote repository, i.e. adds your local branch to it. NOTE: At this point your changes still exist as an independent version, all this step does is make this version visible to your collaborators.
  5. Once you have finished your current task (in this example revising the text processing income code) and made sure it runs ok in Stata, you can merge your changes (branch) into the master version. To accomplish this, in GitHub desktop go to Branch\Create pull request (ctrl-R), which will open up the github.com repository and take you to "Open a pull request". (If you haven't published or pushed your branch to the remote repository, you will prompted to do so now.) Here you can review conflicts, if any, add more description of what your changes do, add people who you want to review or check your changes, etc. 
  6. When you are ready to merge in your changes, click the green "Create pull request" button. If github can handle the merge itself, then you can click the new green "Merge pull request button", then "Confirm merge". Now you have updated the master version of the file(s) with your changes and your branch is redundant, so you can delete your branch with the "Delete branch" button that should appear once the merge is successful.
  7. This completes your complicated revision, which now exists in the project history as a separate branch, like a sub-project.

### 4. Issue reporting
  1. Bug: When you find a coding error or problem in any of the core files or raw data, report it! Go to https://github.com/noellert/CSSCD, click on the "Issues" tab, and add a new issue describing the problem, it's location and type, what project or goal it is associated with, and who should care about it. Label it as a "bug". Then click the green "Submit new issue" button to post it. If you cannot continue your work without resolving the issue, then after you post it, resolve it yourself. Otherwise save it for later or for someone else to do.
  2. Enhancement, question, etc.: You can also post ideas for improvements or revisions, questions, etc. under issues. Just use the appropriate labels provided to categorize your post.
