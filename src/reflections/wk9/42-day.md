3/30/2021
Read Working In a Professional Environment > Github Actions and How to Use Them and answer the following questions

What is a Github action and how do they work?
Github actions are standalone commands that are combined into steps to create a job. Actions are the smallest portable building block of a workflow.

What benefits do Github actions provide?
Github actions makes it easy to automate all your software workflows. Making processes easier and quicker for you in the longrun.

What types of trigger actions can a workflow use? What do they do? 
Workflow, scheduled, webhooks, and external. 
You can configure workflows to run for one or more events using the "on" workflow syntax.
The "schedule" event allows you to trigger a workflow at a scheduled time.
You can configure your workflow to run when webhook events are generated on GitHub. 
You can manually trigger workflow runs. To trigger specific workflows in a repository, use the workflow_dispatch event. 