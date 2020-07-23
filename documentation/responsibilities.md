# Documentation Responsibilities for All Support Technicians

Contributing to our online documentation is the responsibility of all of our Support Technicians. To that end, we have implemented the following practices to ensure our docs get appropriate attention and are reviewed and updated rigorously. The Docs Project Manager \(DPM\) has [specific roles to play in documentation](documentation/management.md), but all Support Technicians have daily roles to play as well. This article walks through those responsibilities.

## Daily Check-ins

Every day in the `#documentation` Slack channel, there is a reminder to post your Docs status update. When that reminder comes in, you should be able to report on three things:

1. What I worked on yesterday \(or the previous work day\).
1. What I am working on today.
1. Any blockers keeping me from doing that work today.

## Using The Feedback Site for Docs Feedback

Throughout your daily interactions with customers and users, you'll be referring to our docs and you might also get feedback about our docs. Part of your contribution to our online documentation is to provide those insights and feedback to our Docs team.

We provide that feedback via the [feedback site](https://feedback.givewp.com). 

Part of your daily tasks can be reviewing existing feedback, voting on posts, commenting on them with additional insights, linking to new Help Scout threads that give more user feedback, and -- of course -- creating new feedback. 

### Creating Docs Feedback Posts

#### Document Name
Docs feedback titles should either be able to complete the sentence "I'd like to learn about \_\_\_\_\_\_\_\_ in the docs" or follow the Bug Report pattern of `{x} should ...` where `{x}` is the current doc or doc section that is incorrect.

#### Category
There are two categories of docs feedback:

**Web Documentation** - Use this category when user-facing functionality needs web documentation outside the product on our website.
**Contextual Documentation** - Use this category when user-facing functionality needs contextual documentation inside the product

##### Some examples of contextual documentation:
All contextual documentation in this screenshot is highlighted in red:
![Contextual documentation is included within the plugin itself](/assets/contextual-doc-examples.png)

Field descriptions and tooltips are among the most common types of contextual documentation.
The link in the bottom right corner is an example of contextual documentation that leads to further web documentation.

#### Details
Use the Details box to give as much context as needed for what is currently missing or incorrect in the documentation. Remember that this is public, so keep the initial details as generic as possible, and add further details as an internal comment. 

#### Comments
Once the feedback post has been created, use internal comments to add as much detail as possible, so that the DPM has enough information to create the doc task in Asana. Additionally, add as a comment \(with a link\) any feedback recieved in other channels \(Priority Support, Facebook, etc\) or customer/user insight that helps to explain the need for the documentation.

#### Voters
On documentation feedback, adding voters is not necessary unless a customer specifically requested the documentation. If so, add them as a voter.

These posts are processed by the DPM and Head of Support to create the Asana tasks for the entire Support Team to implement. 

![A sample Docs feedback post.](/assets/canny-documentation-feedback-details.png)

{% hint style="info" %}
**Important**  
Keep in mind that the feedback site has a public-facing side. When you post new feedback, don't reveal anything about users or customers at all. If you need to reference a user or customer in a comment, you can set that as an internal comment only. Even then, it's best simply to avoid posting any sensitive information into the feedback site at all.
{% endhint %}

## Using Asana

Once feedback posts are recieved and processed by the DPM, they are prioritized and added as tasks in Asana.

The feedback site is a look at _what needs to be done_. The Asana board, by contrast, is a look at _what we are currently working on_. 

![The GiveWP Web Doc Issues board in Asana.](/assets/asana-givewp-docs-board-view.png)

The DPM creates tasks in Asana, and assigns them to technicians, leaving them in the "To Do" column. 

Technicians manage their tasks and move them to the appropriate column as they progress on their docs. 

The DPM and Head of Support are responsible for the "For Review" and "Approved/Ready to Publish" and "Complete" columns. 

Most docs need to be created in Google Drive before being published on the site. The technician should link to the Google Doc in the Asana task as a comment as soon as they begin working on the doc. Assets like screenshots and videos are placed in Google Drive separately, and then referenced in the Google Doc with brackets including alt text: `[picture-1.jpg alt: screenshot showing the Form edit screen, highlighting the Display tab]` This makes it easier to copy and paste content into the website. 

Once the Doc is ready for review, it should go through this process:

1. Technician moves the task to the "For Review" column.
1. DPM loops in SEO team member from the content team to suggest edits for SEO purposes. 
1. DPM approves those edits
1. DPM reviews the Google Doc for the following:
    - [ ] Grammar is correct
    - [ ] No First Person language
    - [ ] Content is accurate 
    - [ ] Screenshots are visible, helpful, and include alt text
1. DPM assigns the task to the Head of Support for final approval
1. Head of Support approves post by moving it to "Approved/Ready to Publish" or sends back for edits by moving it to "In Progress"
1. If approved, DPM publishes the post on the site.
1. Once published, DPM has the technician who wrote it view it on the site to confirm everything displays correctly.
1. Task is marked as complete and moved to the "Complete" column.


At the end of each week, the DPM will post a Progress Report detailing what got done each week. Each technician should review that report to be informed of the team's collective work and heed any advice or directives for the next week's Docs work.


