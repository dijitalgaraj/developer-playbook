# JIRA 
### Overview
JIRA is the project management tool we use in all development teams at Dijital Garaj. 

### How we’re using it
We use Kanban for the projects that don't have too much tasks in backlogs.
Even though each project can be different we share some statuses between projects:

Common statuses:
* Backlog - Stories or bugs that will do in the future
* Selected For Development
* In Progress
* Waiting for test (WFT)
* Done

Journey starts with the planning:
* Analyze the stories
* If story can take more than 2 hours, break into small subtasks
* All subtasks should be testable and have a maximum estimation of 2 hours
* All subtask should have a time estimation 
* 1 week or 2 weeks tasks are moved to the 'Selected For Development' according to the priorities
* Version number should be set to these tasks.

### How we proceed
* Before beginning development, you should take a look at our [How to use git](HowToUseGit.md)
* Development starts with taking first task to the "In Progress"
* ##### If you finish the task, there are couple of things to do:
  * Always make your own tests before finishing
  * Enter the time you spent on this task as 'WorkLog'
  * Move task to the 'WFT'
  * Copy the jira issue number (ASMIOS-354), and use it in your <strong>git commit message</strong>
  * Also don't forget to push your commits after every task.
* ##### If you can not finish the task, there are couple of thing you should do, too:
  * Enter the time you spent on this task as 'WorkLog'
  * Enter a comment about what you do and why you stopped.
  * If task has a blocker, select the blocker task
  * If blocker task is not available, ask PM to open the blocker task
  * If someone else is going to continue on the task, assign the task
  * If you continue to work on the task you can stay it on In Progress
  * But if you will work on a different task, you should move the unfinished task to the 'Selected For Development' 
