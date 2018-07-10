# Managing Documentation Tasks

Online Documentation is a never-ending and vast project that is ever-changing. The only way to ensure that work on docs is done in an efficient manner with no overlap between technicians is to manage the tasks in a transparent and central place.

Properly managing our online docs requires the following:

* Project Management Tool
* Reporting on your Tasks
* Coordinating with the Development Team

## Project Management Tool

We use Github for project management for our Documentation. Github is not intended as a project management tool. Using Github in this fashion means team members do not have to be trained or be familiar with another tool in their daily workflow.
 
Additionally, when a new doc needs to be written for an upcoming feature, we're able to tie that doc to the Github issue on the plugin repository directly (see "Coordinating with the Development Team" below). 

{% hint style="info" %} While Github isn't a project management tool, it's convenient for our team and has several key advantages. {% endhint %} 

To that end, we use Github as a Project Management tool in the following ways:

###Creating Docs Issues
Every significant change or update to our docs starts by creating a new Github issue. Our docs issues are public [here ](https://github.com/WordImpress/Give-Docs/issues "Give Docs Github Repository"). 

Because our Docs are very tightly related to development workflow, we generally follow similar protocols for issue creation. Specifically when it comes to titles of issues, we follow the [Give Github Communication Standards](https://github.com/WordImpress/Give/wiki/Git-Communication-Standards) regarding [Prefixes](https://github.com/WordImpress/Give/wiki/Prefixes "Give Github Communication Standards on Prefixes"). 

The "type" for all Docs issues is always "web-doc"; whereas the "scope" should follow other standards in regard to which part of the plugin or add-on needs addressing in our online docs.

An example of a Github issue with a proper prefix is:

`web-doc(admin-email): update Email Notifications doc with new tags`

From this we know that a Documentation article related to the admin email setting needs to be updated. 

The Give Docs repository has an issue template that is very detailed and helpful, here. It is in the team's best interest that everyone follows the issue template closely, so that documentation can get high-quality attention each day.

### Assigning Issues

After docs issues are created, either the Head of Support or Senior Support Technician will assign a team member that issue. You can learn all about [how assignments on Github works here](https://help.github.com/articles/assigning-issues-and-pull-requests-to-other-github-users/ "Github Help regarding issue assignments").

When assignments are made, it is the responsibility of the one doing the assigning to set expectations regarding when and how the assigned team member should tackle and close out that issue. For example, some issues may require a Google Doc draft to be reviewed before implementing on the website. Others issues are simple and straight-forward and just need to be fixed directly on the website and closed out.  

### Prioritizing Issues
Not all docs issues are created equal. Some issues are urgent, while others might be an ongoing goal. 

Support Leadership will indicate urgency by using Milestones. For example, a Milestone might be created that is connected to a specific Give version release. This means that the issues tied to that Milestone need to be completed by the time the new Give version is released. 

While there is always documentation work to be done, issues that are connected to any Milestone should be treated as the first priority.

If none of the issues that are assigned to you are in a Milestone, the prioritization of them is up to you. 

## Reporting on Your Tasks

All Give-Docs Github activity is sent directly to our team Slack channel (#documentation). Therefore, communicating what you have worked on is best done on the Github issue itself, preventing duplicate work of reporting additionally in Slack. 

It is best to comment on whatever issue you work on daily. This helps Support Leadership be informed of the work you have done regardless of whether there something to show for it yet or not. Some docs issues might require research or gaining new experience with an add-on or feature. 

If you do not have any documentation issues assigned to you, that is a good time to:

    a. Let the Head of Support know that
    b. Review the online docs to create new issues 


## Coordinating with the Development Team
Often, a Milestone will be inherited from the development workflow. For example, [the Give Development Team works in Sprints](https://github.com/WordImpress/Give/wiki/Sprints). When the Development Team is in their final Sprint before a release, the docs issues tied to that release will be added to the same Sprint. This helps ensure that everyone both in Support and Development understand the urgency of the issues as well as make sure changes made to the code during that Sprint are communicated to Support so that Docs can be as accurate as possible.

{% hint style="info" %} Keep in mind that the documentation writing experience itself can sometimes be instructive in highlighting user issues that might need to be improved upon before release.  {% endhint %}

If there is an upcoming feature or new add-on that you are responsible for writing docs for, it is your responsibility to stay updated with the development of that feature, testing it locally and becoming the expert on that feature or add-on.



