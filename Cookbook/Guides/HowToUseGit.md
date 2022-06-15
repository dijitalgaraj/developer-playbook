# Git
### Overview
Git is the version control tool we use in all development teams at Dijital Garaj.

### How we’re using it
We use GitHub to store our repositories. Our way of using git:

  * Every project should have git
  * Every project should have 2 branches:
    * Main
    * Development
  * #### Main Branch
  * There should NOT be any other branches published on GitHub
  * Main branch should have the latest commit that the live version of the application have
  * Every commit in the Main branch should have a version number tag
  * #### Development Branch
  * Development branch is the place we work on
  * Development branch should be merged into Main branch only when the application live on the app store, with the version tag

### Development Process
Steps to follow while working:

  * Take any task from Jira and move it to the 'In Progress'
  * Pull latest commits from 'development' branch
  * Create new sub branch from 'development' branch with the name of your story number (ASMIOS-354)
  * If your story has subtasks, create another sub branch from the story branch, with the jira number of the subtask
  * #### Finish the task
  * When you finish the subtask, commit your codes with the message starts with the jira issue number (ASMIOS-354)
  * Test it!
  * Merge branch into story branch and create another subtask branch until all subtask are done
  * When all tasks of the story is done, test it.
  * Fix your bugs in the story branch. 
  * When you sure with your test, pull the 'Development' branch commits into your story branch and merge them. 
  * Test the application to be sure the merge process is success
  * If there is a problem after merge, fix it. 
  * When you sure with your test, push your commits into 'Development' branch
  * Then you can delete your story and task branches from your local. 