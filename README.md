# github-file-system
This is the code for a personal file storage system which will save all files from your machine to the cloud and auto-commit.

Idea Notes:
** Using Shell Scripts to run on Mac: https://www.youtube.com/watch?v=x5BRVeI76rw

** Using Crontab - schedule scripts/basic commands: https://betterprogramming.pub/https-medium-com-ratik96-scheduling-jobs-with-crontab-on-macos-add5a8b26c30
      * crontab -e opens vim and lets you edit or add jobs
      *   i - insert/edit in vim
      *   esc - get out of edit
      *   :wq - exit vim
      * crontab -l lists all active jobs

Current Where I am:
* I can manually use my script to do all of the git operations and display a notification
* I can automate calling the script using crontab (shown above) but it does not update on GH
* Assumption:
  * I don't have github credentials properly setup in Crontab so it fails the push to remote
