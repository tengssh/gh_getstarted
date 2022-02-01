# Getting Started with Github & Git
- [Quick Start](#quick-start)
- [Adding Collaborators](#adding-collaborators)
- [Using Git](#using-git)
- [Miscellaneous](#miscellaneous)
- [References](#references)

## Quick Start
* Regisiter for a Github account
* Create a new repository <br />
  1. Select **New repository** from the drop menu <br />
  <img src="images/gh_menu.png" width="200"> <br />  
  2. Create a new repository <br />
  <img src="images/gh_new_repo.png" width="600"> <br />
* Upload files <br />
  <img src="images/gh_upload.png" width="400"> <br />
* Edit files & commit changes <br />
  1. Click the “Edit” button <br />
  <img src="images/gh_edit.png" width="200"> <br />
  2. Commit changes <br />
  <img src="images/gh_commit.png" width="700"> <br />
* History versions <br />
  1. Click “# commits” <br />
  <img src="images/gh_page.png" width="600"> <br />
  2. Show commits-history <br />
  <img src="images/gh_commits.png" width="700"> <br />
  3. Show differences <br />
  <img src="images/gh_modified.png" width="700"> <br />
* New branch <br />
  1. Type in the new branch’s name <br />
  <img src="images/gh_branch1.png" width="300"> <br />
  <img src="images/gh_branch2.png" width="350"> <br />
  2. Edit files & commit changes
* Pull request & merge
  1. Edit files & pull request <br />
  <img src="images/gh_pull_request1.png" width="500"> <br />
  2. Merge pull request <br />
  <img src="images/gh_pull_request2.png" width="600"> <br />
* Revert changes <br />
  <img src="images/gh_revert.png" width="700"> <br />

## Adding Collaborators
* Manage Access <br />
1. Click “Settings/Manage Access” <br />
<img src="images/gh_access.png" width="500"> <br />
2. Invite collaborator(s) <br />
<img src="images/gh_invite.png" width="250"> <br />

## Using Git
* Create a new repository
* Clone from remote <br />
  - In your Github page <br />
  <img src="images/git_https.png" width="300"> <br />
  - In your local machine
    ```bash=
    $ git clone <HTTPS_ADDRESS>
    ```
* Git configuration
```bash=
$ git config --global user.name "name"
$ git config --global user.email "username@users.noreply.github.com"
```
* Edit files from local
* Push to remote
  1. Add changes in the *working directory* to the *staging area*
    ```bash=
    $ git add <YOUR_FILES>
    ```
  2. Commit changes to the local *repository*
    ```bash=
    $ git commit -m "YOUR COMMENTS"
    ```
  3. Push to the remote
    ```bash=
    $ git push origin main
    ```
* List history versions
  ```bash=
  $ git log
  ```
* Reset changes
```bash=
  $ git reset <COMMIT>
  ```
* Revert changes (hard reset)
```bash=
  $ git revert <COMMIT>
  ```
* New branch
  1. List current branches
  ```bash=
  $ git branch
  ```
  2. Create a new branch
  ```bash=
  $ git branch <NEW_BRANCH>
  ```
  3. Switch branch
  ```bash=
  $ git checkout <BRANCH>
  ```

## Miscellaneous
* `git status`: Check status
* `git diff`: Compare difference between working directory & local repository

## References
- Github
  - http://guides.github.com/activities/hello-world/
  - https://docs.github.com/en/github/getting-started-with-github/quickstart
- Git
  - https://docs.github.com/en/github/getting-started-with-github/set-up-git
  - http://swcarpentry.github.io/git-novice/
  - https://www.freecodecamp.org/news/learn-the-basics-of-git-in-under-10-minutes-da548267cc91/
