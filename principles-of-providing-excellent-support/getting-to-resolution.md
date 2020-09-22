# Getting to Resolution

Every interaction with every customer, beginning with our first response, has a singular goal: getting to resolution.

Another way we say that is that our customers' success with online donations is our first priority.

We intend to solve our customers' issues in 3 replies or fewer. A resolved ticket is one that has at least one reply from the customer after the initial contact, and has been marked closed by us. We don’t mark a ticket as closed until it is confirmed resolved, or the customer has not replied after a few days and after we have followed up asking for confirmation.

## Problem Solvers, not Guessers

To get to resolution, we need as much context as possible from our users. There's a temptation to take two different shortcuts which represent the tension between what is our role as experts and their role as the owner of their web domain. 

On the one side is the temptation to ask the customer to "deactivate all plugins," while on the other is the temptation to jump straight to requesting admin access to their live site. 

Both of those extremes are indicators that we are guessing at a solution instead of moving toward resolution.

### Deactivating All Plugins

A common refrain in WordPress support is "have you tried deactivating all plugins?" to resolve an issue. Asking the user to deactivate all plugins is asking them to:

1. do additional work after already having a frustrating experience with our products.
2. disrupt the experience of site visitors.
3. technically troubleshoot an issue that we are far better equipped to troubleshoot. 

There are times when deactivating plugins is the most effective way to isolate the source of the issue. In those cases, the recommendation should be because we, the experts, know with certainty that this will resolve the issue. We should frame the act as temporary, and a diagnostic tool to confirm our educated guess. Also, reassure the user that if a conflict with another plugin and ours is discovered in this process, we will work to find a workaround for the conflicting plugin or theme. 

Lastly, whenever possible, if a staging site is available, or a full-site duplicate is available, using those for the deactivation process is preferred. When none of those are an option, point the customer to [our detailed tutorial on using the Health Check plugin](https://givewp.com/documentation/resources/troubleshoot-wordpress-websites-health-check/) as a last resort.

### Asking for Credentials

Sometimes the most effective way for a technician to fully understand a problem is to login to the customer site itself. But there are several ways to get that access that do not put the customer's live site at risk. Whenever possible we want to avoid logging into a live production environment.

Additionally, asking for admin credentials is an indication that the technician is guessing at a solution, instead of seeking the correct information to resolve the issue. 

Before asking for credentials to a live environment, we should first attempt to resolve the issue by:
* Asking for access to full-site backup that we can replicate locally
* Asking for access to a live staging or development environment

If none of those options are available, then we ask for live site credentials, but with a lot of care and context. Requests for admin credentials should have at least three things in them:

1. Context. What _exactly_ are we going to do with those credentials?
2. No-gos. What specific things are we _not_ going to do?
3. Responsible recommendations on how to handle those credentials. The following canned reply should be used for all credential requests.

> Here's the best way to send us temporary secure credentials:
> 
> 1) Create a NEW user account with the email address \_\_\_\_\_\_\_\_\_ and let WordPress generate a strong password for you.
> 2) Make sure that the User Role is set to "Administrator" -- this is necessary to see all the items that we need.
> 3) Make sure WordPress does NOT send an email
> 4) Go to https://quickforget.com/ and paste your credentials (with URL to the login page) there to create a secret URL. Set it to save for at least 48 hours. Reply here with that URL and it will expire after we open it once. This is a security precaution so you don't have to email credentials.
> 5) Once this ticket is resolved, delete that whole user account for security purposes
> 
> If you need more of a walkthrough on that, here's a screencast showing how to send us credentials: https://shortnit.com/creds

{Section on following-up with customer to delete our admin account, and also to delete site duplicates from Drive}.

## Help Scout Protocols
In order to more objectively know that we are working toward resolution, we measure it based on several important metrics in Help Scout.

* First Response time
* Responses until Resolved
* Number closed per week 

In order for these metrics to reflect resolutions as closely as possible, it's important that each support technician follow these basic protocols when resolving customer issues. 

### Managing First Responses
The first response is always marked as Pending, waiting for the customer to confirm the fix. We encourage a response from the customer, so that we can confirm that fix, and have an additional touch-point with the customer.

### Closing Conversations that Do not Get Replies
Occasionally the customer simply doesn't reply to our responses. But it is our goal to always have confirmation that the customer issue is in fact resolved. 

So if a customer does not reply to our first response, we reach back out within 3-5 days with the `close` saved reply from Help Scout, and if no response then, close without a third reply.

Unfortunately, some customers will not reply to a ticket that has been resolved no matter how often we ask. For that reason, we close tickets after reaching out for resolution and checking Help Scout to confirm that the customer viewed the response.

### A Note about the Difference between Closed and Resolved in HelpScout reports
Help Scout considers a ticket "resolved" only when the following things are true: 1. The customer has responded. 2. The support tech has marked the ticket as closed.

This is a crucial piece in understanding not only how we push toward a resolution, but also why we leave tickets as pending until they are confirmed to be resolved by the customer. The best way to confirm that an issue is resolved is by the customer responding to confirm, which is the goal.

In our reporting, both the number of tickets closed, and the resolve ratio are significant, but for different reasons. 

* The number of tickets closed shows us the total number of tickets the team has resolved in a week. Comparing that number to the total new tickets generated helps us understand how effectively we are clearing out the queue.

* But "Resolutions" often do not include tickets that are "closed" in HelpScout. They do however tell us how many replies we sent before it became resolved. That, combined with the average time on ticket, helps us understand how much time we are spending on priority support issues as a team and individually. 