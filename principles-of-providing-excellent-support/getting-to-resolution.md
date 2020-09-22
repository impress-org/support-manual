# Getting to Resolution

Beyond the first response, every interaction with a customer in support has a singular goal: we get to resolution.

We solve our customer’s problems, in 3 replies or fewer. A resolved ticket is one that has at least one reply from the customer after the initial contact, and has been marked closed by us. We don’t mark a ticket as closed until it is confirmed resolved, or the customer has not replied after a few days and after we have followed up asking for confirmation.

## Help Scout Protocols
The first response is always marked as Pending, waiting for the customer to confirm the fix. We encourage a response from the customer, so that we can confirm that fix, and have an additional touch-point with the customer.

If they do not follow up, we reach back out 3-5 days later with the “Close Ticket due to inactivity” canned response from Help Scout, and if no response then, close without a third reply.

Help Scout considers a ticket "resolved" only when the following things are true: 1. The customer has responded. 2. The support tech has marked the ticket as closed.

This is a crucial piece in understanding not only how we push toward a resolution, but also why we leave tickets as pending until they are confirmed to be resolved by the customer. We agree with Help Scout that the best way to confirm that an issue is resolved is by the customer responding to confirm. It also creates another touch point with the customer, which we value.

Some customers, no matter how often we ask, will still not reply to a ticket that has been resolved. For that reason, we close tickets after reaching out for resolution and checking Help Scout to confirm that the customer viewed the response.

In our reporting, we report on the close rate \(trusting that support techs only close issues that are resolved to the best of our knowledge\), and also on the resolve rate, which is the official Help Scout metric.

## Problem Solvers, not Guessers

To get to resolution, we need as much context as possible from our users. There's a temptation to take two different shortcuts which represent the tension between what is our role as experts and their role as the owner of their web domain. 

On the one side is the temptation to ask the customer to "deactivate all plugins," while on the other is the temptation to jump straight to requesting admin access to their live site. 

Both of those extremes are often indications that we are guessing at a solution, instead of moving toward resolution.

### Deactivating All Plugins

A common refrain in WordPress support is "have you tried deactivating all plugins?" to resolve an issue. We don't put that work on the user of our plugins. Instead, we solve problems. 

In addition to the indication that we are merely guessing instead of solving the problem, asking the user to deactivate all plugins \(or similar diagnostic steps\) is asking them to 
1. disrupt the experience of site visitors.
2. technically troubleshoot an issue that we are far better equipped to troubleshoot. 

The recommendation to "Deactivate All Plugins" should be because we, the experts, know that this will resolve the issue. We should frame it as temporary, and a diagnostic tool to confirm our educated guess. Also, reassure the user that we will work to find a workaround for the conflicting plugin or theme. We solve problems.

To clarify using a simile, imagine a scenario where you visit a surgeon, complaining of pain. "Deactivate all Plugins" would be the equivalent of the surgeon asking you to take 15 pills and let her know which one works. 

We, like that surgeon, must give an educated, specific, and clear diagnosis. If that means asking more clarifying questions until the true cause of the problem shows up, that's far better than guessing and asking the user to confirm. We don't guess, we gather enough information to solve problems.

### Asking for Credentials

Asking for admin credentials \(especially early on in the life of a ticket\) is an indication that the technician is guessing at a solution, instead of seeking the correct information to resolve the issue. 

Admin credentials to live sites should be treated as sensitive data. When at all possible, we should attempt to get staging or development site access in place of live site access. 

Requests for admin credentials should have at least three things in them:
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