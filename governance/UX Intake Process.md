# UX Request Intake Process

## Background
The UI-UX SIG is responsible for the overall user experience of O3DE and other products or services that the GE&DS team is in charge of. We focus on two streams of work:

1. **Strategic focused projects** that are usually planned from the beginning of the year and require dedicated UX design resources to work on for a long period of time.
2. **Ad-hoc requests** that are usually unplanned, the effort varies depending on the size of the projects. They include UX review and approval for a pull request, UX work to unblock a GHI ticket, or commenting on a question in a GHI or JIRA ticket.

This **UX Request Intake Process** is to address the second stream of work, *the ad-hoc requests*, specifically. This will allow us to provide better support for the team, arrange the UX resource accordingly, and raise the quality of our UX deliverables.

## SIG Community Responsibility

### *Q1: What needs to be reviewed by the UX team / SIG-UI-UX?*

Any tickets that has a user facing element in it (e.g., user workflow, UI pages, UI/error messages, etc.), their solutions need to be reviewed and approved by SIG-UI-UX before releasing to the public.

### *Q2: How do I get the UX team / SIG-UI-UX to review or work on my tickets?*

* Step 1, add “**SIG/UI-UX**” label to your GHI ticket if it has a user facing element in it.
* Step 2, answer the following questions to determine what help you need from the UX team / SIG-UI-UX.
    * If the ticket requires a UX solution before the dev team can work on it, add “**needs-UX-action**” label to the ticket, then move to Step 3.
    * If the team is able to propose a UX solution but needs SIG-UI-UX to review the solution before implementation, add “**needs-UX-review**” label to the ticket, then move to Step 3.
    * If the ticket is a pull request and requires SIG-UI-UX approval before releasing to the customers, answer the following question- have you reached out to SIG-UI-UX before the pull request is created?
        * If YES, move to Step 3.
        * If NO, go to "**Q4: What if I fail to involve SIG-UI-UX or involve SIG-UI-UX too late for my tickets?**"
* Step 3, attend SIG-UI-UX Office Hours **every Thursday at 9am PST** to review your request with us. In the office hours, we will review your requests and determine the following:
    * The urgency of this request.
    * The possible direction of the UX solution
    * If the ticket requires further UX work/cannot be resolved during the office hours, we will create an associate UX ticket in JIRA to account for the work needed for the request.
    * Assign story points.
    * Assign a dedicate UX resource and other related stakeholders to this ticket for visibility.

See *Q7* for how to sign up to the SIG-UI-UX Office Hours.

### *Q3: When should I send my UX request to the UX team / SIG-UI-UX?*

Depending on the size of the request, it will normally take us 1 sprint (we run 2-week sprint cadence) to work on a UX request. We recommend to send the request to us at least 2 sprints/4 weeks ahead of your development plan, so we will have enough turnaround time to cover design, review, and iteration work.

### *Q4: What if I fail to involve SIG-UI-UX or involve SIG-UI-UX too late for my tickets?*

This usually happens when the developed solution is ready to be released through a Pull Request on GHI, and SIG-UI-UX is not involved during the pre-development stage. In this case, you will need to bear the risk that SIG-UI-UX will not approve your request, or we will be delaying your request due to the unplanned status. **You will need to attend the SIG-UI-UX Office Hours to review the Pull Request with us in person.**

### *Q5: How do I know the status of my UX request?*

Once we accept your request in the SIG-UI-UX Office Hours, we will create an associate JIRA ticket for your request and add your name to the ticket. Depending on the priority of the request, we will assign the ticket to the future UX Sprints, and you will receive an update to the ticket. The assigned UX Designer will also reach out to you to get more information.

### *Q6: Do I have to attend SIG-UI-UX Office Hours to review my request? Can I do this offline?*

Yes, we will still review all the tickets that have the correct labels (SIG/UI-UX, needs-ux-action, needs-ux-review) on a weekly basis. However, the response time will be much slower (up to 4 weeks). If you need immediate attention from the UX team / SIG-UI-UX for your request, come to join our Office Hours is the best option.

### *Q7: How do I sign up the SIG-UI-UX Office Hours?*

SIG-UI-UX Office Hours occurs every Thursday at 9am PST on Discord SIG-UI-UX voice channel. You can visit https://github.com/o3de/sig-ui-ux/issues to choose a time, add your topic with the link to your ticket in the comment area, then show up to our Office Hours at the time of your choice. 




