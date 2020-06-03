# A03

***Using GitHub***

1) Start by creating a GitHub account (https://github.com)
  - GitHub is an open source coding system where files and code can be shared and worked on collectively with multiple people
  - Once you sign up, create a repository (central location where files and code are managed) by clicking the "+" sign in the upper right corner. Choose “Create New repository” and name it whatever you like 
  - Make the repository **public** and add the README file. Click **Create**.
2) Install Webstorm (an IDE used to edit and develop HTML and other script code) using a student email if possible (email ending in .edu) and download Git ("an open source distributed version control system") according to your operating system
  - Webstorm Download: https://www.jetbrains.com/student/
  - Git Download: https://git-scm.com/downloads
3) Open Webstorm. In Webstorm press (Ctrl+Alt+S) for system preferences. Select Version control Git. Enter the path to the git.exe (such as C:\Programs\git.exe)
4) Now in Webstorm, create a Git repository by selecting VCS and **Import into Version Control**
  - Select VCS --> Checkout from version control --> Git 
  - Enter Github repository name 
  - Enter local path name
5) Create a Webstorm file
  - Choose File --> HTML --> HTML 5 or File --> Stylesheet
6) The Add file window should open. Click the files you want and hit **Add**. This adds to local file system on Webstorm.
7) **Commit** Changes ("saves" to track all changes that have occurred since last commit)
8) **Push** Change to Remote Repository (uploads local repository data to a remote repository)
  - Remote meaning a shared repository that is used by multiple people, and not personal like your "local" repository
  - The push should now have the files on GitHub (remote repository)
9) Set up Github Pages
  - Click Settings
  - Check the repository name
10) Choose GitHub Page Location
  - Select “Master branch”
  - Note the published URL
11) Check your GitHub Pages by copying the Github.io URL into a browser

Other Definitions:
  - Branch: Path that holds certain data
  - Pull: Opposite of push, used to receive content from a remote repository and update it to the local repository
  - Fetch: Part of pulling data, system goes to "fetch" data from one location and bring it back to the caller
  - Merge: Other part of pulling data, fetched data is now incorporated into the local repository
  - Merge Conflict: Branches that have competing commits, and need to be fixed manually to decide what data gets to stay


Source: (https://medium.com/mindorks/what-is-git-commit-push-pull-log-aliases-fetch-config-clone-56bc52a3601c)
