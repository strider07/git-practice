# git-practice
This exercise will help you get comfortable with the Enye git workflow

# Instructions
Update this repo by taking the following steps:
  1. Create a folder in the root directory of this repo (use any method)
      - name it `week2_{{your_first_name}}`
  2. Create a a file inside of this folder (use any method)
      - name it `git_command_line_assessment_{{your_first_name}}.txt`
  3. In this text file, list 5 commands that you learned from week 1 and explain what they do in your own words
  4. Save the file (__CTRL+S__) then Add and Commit your changes
      - make sure to add a short but descriptive message of the changes that you are committing
  ```
  git add git_command_line_assessment_{{your_first_name}}.txt
  git commit -m "{{add_your_message_here}}"
  ```
  5. Now the changes to your forked version of the `git-practice` repo
  ```
  git push origin master
  ```
  6. Go to your forked and make sure that the changes have been successfully pushed to github
  7. Once you have the confirmation, slack the link of you forked repo to __enye_admin__


### Additional Useful Commands
  * `git status` - to see which files that you have changed
  * `git add .` - to add all files
  * `git commit -am "{{add_your_message_here}}"` - to add all files during a commit (meaning you add and commit in one step instead of two)

### Advanced commands
  * `git branch` - lists all the local branches
  * `git remote -v` - list all the remote repos connected to your local repo (by default origin points to the git repo that your cloned from)
  * `git checkout {name_of_branch}` - switches you to that branch
  * `git checkout -b {name_of_branch}` - creates a new branch and switches you to that branch
  * `git branch -d {name_of_branch}` - deletes the named branch
  * `git push origin -u {name_of_branch}` - creates a new branch in the remote repo
