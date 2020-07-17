# Managing Tasks for Docs

The role of the Docs Project Manager is crucial to the success of our online documentation. This article describes the process and daily responsibilities this role has in managing all the tasks for online documentation maintainance and improvement.

Online Documentation is a never-ending and vast project that is ever-changing. The only way to ensure that work on docs is done in an efficient manner with no overlap between technicians is to manage the tasks in a transparent and central place. 

Properly managing our online docs requires the following:

* Managing Docs Feedback and Turning it into Tasks
* Managing and Tracking all Docs Tasks
* Reporting on the Work Done on Docs Weekly
* Coordinating with the Development Team

## Managing Docs Feedback and Turning it into Tasks

We use [Canny](https://canny.io) for receiving and processing feedback for our online docs. The role of the Docs Project Manager is to process all incoming feedback and take action on it. That is done via three main steps:

1. Processing new posts
2. Adding additional insight/context to existing posts
3. Converting posts into actionable and detailed Asana tasks

### Processing New Posts

As new posts come in, the Docs Project Manager will review them and update their status as the feedback gets action. Here is the list of actions and what they mean for us as a team:

* **Open** -- this post has not yet been reviewed by the Docs Project Manager and needs attention.
* **Under Review** -- this post has been reviewed by the Docs Project Manager and needs additional information or more feedback before becoming actionable.
* **Planned** -- this post has been reviewed and has enough detail and needs to be made into an Asana task.
* **In Progress** -- this post has been made into an Asana task and is actively being worked on.
* **Complete** -- this post was made into an Asana task and the work is done and published on the website.
* **Closed** -- this post will not be worked on. This is similar to the Github concept of `wont-fix`.

### Adding Additional Insights/Context to existing posts

This is a responsibility of the entire Support Team, but it is vital that the Docs Project Manager be on the lookout at all times for opportunities to add new insight to existing feedback.

This can be done by adding new users to Canny to represent additional voices and votes to existing issues. If you hear of similar feedback in Slack or via Help Scout threads, or social media platforms, you can add that person (with or without their email address) to indicate that more than one person agrees with this feedback.

![Adding additional users as votes to an existing feedback post in Canny](/assets/canny-adding-another-voter.png)

### Converting posts into actionable and detailed Asana tasks

Lastly, action cannot be taken until the feedback is turned into actionable tasks. Turning feedback into tasks should happen as soon as enough context and detail is available in the feedback for the task to be actionable. 

Details for creating Asana tasks are in the next section below.

## Managing and Tracking all Docs Tasks

We use Asana for managing docs tasks. One of the primary responsibilities of the Docs Project Manager is to convert feedback (in Canny) to actionable tasks in Asana and assign them to relevant team members.

There are generally two types of tasks that can be created: New docs, Existing Doc Updates. 

There is a Task Template in Asana for each type of update.

* [TEMPLATE: New Doc]
* [TEMPLATE: Doc Update]

Every time you create a new task you should duplicate a template to start that task. That is done by opening the task template, clicking on the three dots in the top-right, and selecting "Duplicate Task"

![Duplicating a task template in Asana](/assets/asana-duplicating-a-task-template.png)

Once duplicated, the Description and sub-tasks spell out the necessary information. 

{% hint style="info" %}
**Pro Tip**  
It's important that the feedback you have from Canny is enough to create this task. If it isn't, you need to go back to those who provided the feedback to get more insight.
{% endhint %}

### Assigning Tasks

Once a task is created in Asana, it is placed in the "To Do" column of the board. From there, the Docs Project Manager assigns the issue to a team member, which alerts that team member. Once the team member begins work on a task, they move it to "In Progress" to indicate to the team that they are working on it. 

Each team member in docs should have one task in "In Progress" at all times, and should use their daily standup in the #documentation Slack channel to report on progress of their assigned in progress task\(s\).

### Prioritizing tasks

Not all docs tasks are created equal. Some tasks are urgent, while others might be an ongoing goal.

The docs project manager \(with the help of Support Leadership and Development\) is responsible for prioritizing docs tasks so that critical errors and omissions are resolved. 

Prioritization becomes more acutely important in advance of and immediately following major releases of the product. During these times, tasks are tagged to indicate being a part of the release, and those tasks should be prioritized. This is done by the docs project manager during the QA portion of the development team's release cycle.

## Reporting on Weekly Docs Progress 

Every Friday, the Docs Project Manager should post a "Progress Report" in Asana and post the link in the Slack #documentation channel for all to review. 

This weekly Progress Report should have the following elements:

* A summary of the work done this week
* How many new docs were published this week
* How many doc updates were published this week
* How many feedback posts were processed
* How many new tasks were created
* How many tasks are overdue
* General directive for how to succeed with docs next week

## Coordinating with the Development Team

The product managers on the development team, along with the developers themselves, are in charge of making sure that enhancements and changes to the product that require modification of the online docs are tagged in a specific way within the GitHub repositories. 

It's the role of the docs project manager to regularly consolidate issues from GitHub into tasks in Asana, and to tag those tasks in conjunction with a release, when applicable.

{% hint style="info" %}
Keep in mind that the documentation writing experience itself can sometimes be instructive in highlighting user issues that might need to be improved upon before release.
{% endhint %}

