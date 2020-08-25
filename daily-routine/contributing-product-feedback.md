# Creating and contributing to Product Feedback

As a part of our role of customer ambassador, when we find a problem, bug, or area for improvement in the plugin or an add-on, we escalate it to the product team in the form of a post on [the GiveWP feedback site](https://feedback.givewp.com/) \(powered by Canny\). This is done during ticket time, as a part of the flow.

Any time we create feedback on the site that is based on a request from Priority Support, we add a note to the Help Scout ticket with a link to the feedback. 

The feedback site is designed to provide a space between "Users are requesting this issue" and "the development team is working on this issue" so that support technicians can always tell what is being actively worked on during the current development cycle \(it's on GitHub\) and what is still being evaluated for inclusion in a future development cycle \(it's in the feedback pipeline and marked accordingly\).

There are three types of product feedback:

1. Bug Reports
1. Feature Requests
1. Documentation 

The first two are discussed here. For more on Documentation feedback, see the section on [Managing Docs](/documentation/responsibilities.md#using-the-feedback-site-for-docs-feedback). 

{% hint style="warning" %}
**NOTE**  
The Bug/Feature Name and Details entered here are all publicly viewable. User information of any type should be removed from feedback.
{% endhint %}

## Bug Reports

If in the course of replicating customer issues we find a bug that is replicable in a separate environment, we should immediately create feedback, and alert Senior Support Technicians and/or the Head of Support that the feedback has been reported. It's not the role of Support Technicians to determine if an issue is urgent, just to keep an accurate count of how many folks are reporting an issue. 

To create the feedback for bugs, visit the [bug reports page of the feedback site](https://feedback.givewp.com/admin/board/bug-reports) and click to create new feedback. While filling out the title and description of the feedback, ensure the bug has not already been reported. using the column on the right.

![Reporting Bug Report Feedback](/assets/canny-create-bug-feedback.gif)

If the bug is not already reported, use the left-side interface to report a new bug. 

### Bug Name
The title of the bug should be short and descriptive and communicate what is broken. `{X} should...` language is helpful, and titles should remain as end-user understandable as possible. 

* **Ineffective Bug Name:** `Race conditions should be avoided on the init hook`
* **Instead:** `Email reports should include renewals`

### Details
In addition to a short and descriptive title, Bug Reports need 1-2 paragraphs demonstrating the bug replicated in a fresh environment. The goal of this section is to communicate \(in user-understandable language\) how to replicate the problem. 

## Feature Requests

GiveWP is constantly adding new features via add-ons, enhancements of existing functionality, and new integrations. We use the feedback site for aggregating and tracking the number of users asking for a specific feature. Feature requests are different from bug reports in two key ways:

1. Feature requests are given a category
1. There's no "should" language in the feature name.

{% hint style="info" %}
**Pro Tip**  
The feature name should complete the sentence "GiveWP now supports \_\_\_\_\_\_\_\_\_\_" if there were a blog post announcing the feature some day.
{% endhint %} 

Any time a user or customer expresses interest in a feature, we make note of that by either creating new feedback, or adding voters to existing feedback. The procedure for adding a new voter is the same as for adding voters to Bug Reports.

### Feature Categories

The three feature categories are `New Feature`, `Enhancement`, and `Integration`. Some feature requests fall into multiple categories, at the discretion of the Product Managers. 

#### New Feature
This category is for features that would constitute a functionality that is not present in any form currently in the GiveWP ecosystem. AN example would be `Peer to Peer Functionality`.

#### Enhancement
This category is for adding to or extending functionality that is currently present. An example would be `Additional Content on Receipts`.

#### Integration
This category is for features that require integrating with third party services and APIs. 

## Voting on Behalf of Users
When you create feedback on behalf of users, to keep an accurate count of how many users are reporting the issue, be sure to add them as a voter. Begin by searching the voters already in the system, and then add in the user using the "Add voter" link:

![Adding a User in the Feedback site](/assets/canny-add-voter.gif)

Do not add the voter's email, to prevent them from getting unexpected emails from issues they didn't know they were following.

## Public and Internal Comments
In order to provide as much context as possible, use internal comments to link to Help Scout tickets. Whenever possible, copy the link to the ticket as well as the relevant perspective from the user. Link to the actual reply that has the user's feedback, by copying the URL to the specific Help Scout reply: 

![Finding the correct URL in Help Scout](/assets/help-scout-correct-url.png)

### Internal Comment Markdown Template
To record feedback that comes directly from users/customers use the following template:

```
Firstname Lastname via [Priority Support](URL GOES HERE):
Most relevant feedback from the user gets pasted here.
```

This follows for feedback received from social media, priority support, or anywhere else. Be sure to include the user's name in the comment. \(they should also be added as a voter, if they haven't already\)

If you as the technician have separate feedback from the user, use a separate internal comment. This prevents confusion in internal conversation. 

{% hint style="warning" %}
**NOTE**  
Public comments by admins on the site will trigger emails to all voters and people following the feedback. We almost never use public comments for this reason.  
{% endhint %} 

## Feedback Statuses
​
All feedback posts have a public status that indicates the current state of the feedback. These statuses are set by the Product Manager and kept up to date as feedback progresses into development or is dismissed.
​
### Open
​
Feedback has not yet been processed by the Product Manager.
​
### Under Review
​
Feedback has been processed by the Product Manager who completes the following steps:
​
-   Reviews the feedback and any linked customer insights
-   Determines the priority of the feedback and escalate urgency if needed
-   Categorizes and tags the feedback

This status does not indicate a commitment to take action on the feedback.​

### Planned
​
The development team has committed to addressing the feedback in the next development cycle. At the beginning of each development cycle, the Product Manager will apply this status to indicate that a resolution for the feedback has been planned.
​
### In Progress
​
Development is in progress. At this stage, the Product Manager should have linked the feedback post to a GitHub issue. Once a GitHub issue has been linked, most of the progress regarding development will take place in GitHub.
​
### Complete
​
Feedback has been addressed, related GitHub issues have been merged, and the new or improved functionality has been released to the public. At this point, customers inquiring about this feedback should be directed to the latest release of the product.
​
### Closed
​
Feedback has been dismissed without a resolution. Rationale for dismissing the feedback should be provided on the post.


