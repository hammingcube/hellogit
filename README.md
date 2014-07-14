hellogit
========

### Describing various git workflows (for an absolute beginner)

##### Step 1: Create a repository called test
##### Step 2: Follow these instructions on command line
  ```sh
  touch README.md
  git init
  git add README.md
  git commit -m "first commit"
  git remote add origin https://github.com/maddyonline/test.git
  git push -u origin master
  ```
##### Step 3: Fetch/Merge from the github server (for later use)

  ```sh
  git fetch
  git log HEAD..origin/master
  git merge origin/master
  ```
