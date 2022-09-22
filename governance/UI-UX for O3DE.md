# Contributing to UI-UX SIG

Welcome O3DE contributors! If you are reading this document,it's likely because of one of three reasons: 

1. You are building or modifying a front end feature of O3DE that has some kind of UI 
2. You are contributing to our UX/UI patterns and libraries that you want globalized 
3. Looking for support for UI development autonomy.

If it’s the latter, please note you will have some additional steps needed for your contributions to be accepted and moved into our global patterns. Please review the [UX Patterns for O3DE]() document to learn more. Our hope is that by globalizing all of our UX foundational work, we can keep O3DE from becoming a hodgepodge of tooling. It also provides rules for all of us to follow and includes a set of pre built input types that allow developers to work quickly without needing to get UX sign off.  

We want to provide developers with a simple and easy path to develop new tools and services that look like they are a part of a cohesive O3DE experience.  This will allow for tool builders to do what they do best, and focus on the tools they are creating, rather than establishing new UI designs for each new feature.

## About this document

This document is a living document and its contents will change from time to time as issues are evaluated by the UI/UX SIG in accordance with our charter. If something is not outlined in this document that you are looking for,reach out to us. We are always looking to improve the clarity of our guidelines. 


## What is the UI/UX approval process all about?
The UI/UX approval process helps us keep an eye on new feature work going into O3DE to provide a consistent, delightful, and easy-to-use experience for creators in the engine. When submitting a new feature with a user interface, the UI/UX SIG will be using the following guidelines to approve work.

* Did you follow the UX pattern library and UI 2.0 framework?
* For major changes or new pattern additions, did you get approval from the UI/UX SIG?
* Did you include any additional research in how decisions were made with regards to the design or implementation of your feature?
* Does your feature interact with other gems or editor tools without error?

Following the provided guidelines is your best opportunity to get your content live quickly.  

## Tell me more about the UI/UX SIG?

* The UI/UX SIG meets on a regular basis and reviews any emails, tickets, patterns, or updates being requested. Assigned delegated members will have time to review tickets activities with the group.  
* Members of the SIG are expected to follow the same rules of engagement to add in new content.
* During our meetings, an owner will be assigned to follow up on all activities for a given submission. Their job will be to identify any problems with the current design system in conjunction with QA an the submitter (if needed)
* At the end of the meeting a determination will be made about the submissions and reply to the email with the given determination. In some circumstance the submitter might not get feedback from our team. It is on a case by case bases

### What does the UI/UX SIG review?

We focus on the use cases and example that fall outside our foundational rules / patterns and or changes to the existing rules/patterns. 

*Who is doing the implementation work?*

You are. As work is submitted to O3DE.  If your feature contains user-facing features, please include screenshots and the information below in your PR:  
1. Does your new content include ANY UX related interfaces? 
2. Did you follow the UX Pattern and tool libraries?
3. Did you have any conditions in which you implemented any new patterns, or tools that were not an existing part of the UX libraries?  
       

*Who should be using this system?*
Anyone who plans on delivering any experience that has a customer facing interfaces. 

## Recommendations for creating new user interfaces

* Start by installing O3ED and gaining access to [`QtControlGallery.exe`](https://alpha-docs-aws.amazon.com/lumberyard/latest/userguide/ui20.html#ui20-best-practices)
* Create a “process flow diagram” and or “user flow examples“
    * Attaching these to your final submission helps us review quickly, especially if the feature is large.
* Take a look at the [UI Component library](https://alpha-docs-aws.amazon.com/lumberyard/latest/ui/uidev-component-intro.html) and plan your UI tooling based on the tools and controls you currently have access to. 
    *  If library is lacking a specific input type, component, pattern, or tool you’ll need to submit your new changes through the [UX Patterns for O3DE]() process.
* Avoid writing custom input field types. This causes misalignment and inconsistency in look and feel.  


## Can I make additions and or changes to the UX framework?
Yes! We welcome participation in the UI/UX SIG. You can choose a contribution amount of time that works for you. You can help shape the future of our UX in a couple different ways:
* Help review RFCs PRs, and issues that have a UI/UX component and provide feedback 
* If you are interested in just contributing patterns or tool, see [the O3DE Patterns for O3DE] documentation
* If you would like to contribute as a UI/UX SIG member, join the mailing list and introduce yourself there or in our Discord channel.


## O3DE Sig UX/UI - process, guidelines and quality standard  

In May 2021 we began working on our goal “Build a UX charter with scalable process and guidelines to support community autonomy”. The definition of this goal is; establish the UX process, guidelines and quality standard to enable the community to build consistent and quality user experience in O3DE.”  The definition define below  is not the finish line for us but a baseline we intend to continue to work on and refine. We are currently testing  for a broad number of contributors and learning styles in the community to improve on this model. 

If you're curious about our other Sig Ux UI charter documents, you can read them here. 
**[UX charter](https://github.com/o3de/sig-ui-ux/blob/main/governance/SIG%20UI-UX%20Charter.md)**, **[Interacting with UX Sig](https://github.com/o3de/sig-ui-ux/blob/main/governance/UI-UX%20for%20O3DE.md)**, **[Patterns for O3DE UX /UI](https://github.com/o3de/sig-ui-ux/blob/main/governance/UX%20Patterns%20for%20O3DE.md)**

### So what does the Sig UX-UI charter already have defined? 
* Roles and responsibilities of the Sig UX-UI group.
* How do we handle disagreements. 
* Define our cross-cutting activities and how do we process them. 
* How the Sig UX-UI patterns can be changed or added to by community contributions.
* How do developers submit new UX content that doesn’t require Sig UX UI oversite. 
* A bi-weekly meeting office hours and design review.
* A bi-weekly Sig-UX-UI Charter meeting (Review open tickets, RTE improvements, answer open questions from community).
* Promote design engagement with the O3DE community by openly doing our own internal design review externally. 
* On-call UX rotation (Used for discord responses)
* Create a customer engagement model. 
* Maintaining the Sig email channel for updates and feedback.
* Maintaining Sig calendar to keep track of meetings and times
* Established patterns for meeting notes and documentation for GitHub. 
* Rules for reviewing content (office hours / design review) + document guidelines.

### Sig UX-UI charter items still in progress: 
* Creating a plan on how we will handle new RFC incoming to the Sig UX-UI. 
* Begin publishing our UX pattern (BlueJay design system) so the community can have the same knowledge that we do as UX designers.


### New items we are adding below.
* How do we process GitHub tickets? 
* New "tags" for the GitHub ticket triage process.
* Established new rules on how to evaluate and processing tickets.
* How to promote community contributions.


### Mission Statement (the why):
As the Sig UX UI group. Our job is to be the voice of the customer and actively improve the vision, workflows, and patterns of O3DE. This is accomplished by reviewing and improving user reported problems through different forms of UX methodologies. We are here to promote our UX foundational guidelines and give expert feedback. The Sig-ui-ux team is an active contributors/owner of new features or services being added to O3DE. Unlike most other Sig’s UX-UI is a cross cutting team and that means we need the ability to review tickets and potentially request for additional changes, change direction, or reject work. Each of these kinds of decision would be done in close collaboration with PM or SDM to verify stakeholder agreement.
    

### How are we processing tickets?
We have now established some ground rules about how ticket triage will work. These are the steps until we learn better.
* A Sig-UI-UX Maintainer will drive our Bi-weekly Wednesday Sig Triage calls on tickets. As well as attend the #Sig-Release O3DE Issue Triage on Monday and Wednesday. During these meetings in conjunction with the Sig UI-UX Reviewer community we will apply our tags and status
    * A reviewer will have the ability to add remove tags in open conversation with the community. During that time the reviewer (Sig UI-UX representative) will be able to drive the conversation around what labels should be added and removed. Long term, I would expect that specific reviewer members who earn the label "Sig UX UI staff" would earn these same abilities and could step in to drive these conversations. Please see more about leveling up below.


### Search Queries - Daily:
<table style="border:0px;">
<tr><td width="200px;"> Invidiual Pull request </td><td> https://github.com/o3de/o3de/pulls/review-requested/@me </td></tr>
<tr><td> Mentions </td><td> https://github.com/o3de/o3de/issues?q=is%3Aopen+mentions%3A%40me </td></tr>
</table>

### Search Queries - Triage:

<table style="border:0px;">
<tr><td width="200px;"> Team Pull requests </td><td> https://github.com/o3de/o3de/pulls?q=is%3Apr+is%3Aopen+label%3Asig%2Fui-ux+-label%3Astatus%2Fneeds-ux-approval%2Cneeds-ux-action%2Cstatus%2Fux-approved </td></tr>
       
<tr><td> Blocker / Critical (-UX project) </td><td> [https://github.com/o3de/o3de/issues?q=is%3Aopen+label%3Asig%2Fui-ux+label%3Apriority%2Fblocker%2Cpriority%2Fcritical+-label%3Aneeds-ux-action%2Cneeds-ux-info%2Cstatus%2Fneeds-ux-approval%2Cui-ux%2Fin-design%2Cstatus%2Fux-approved+](https://github.com/o3de/o3de/issues?q=is%3Aopen+label%3Asig%2Fui-ux+label%3Apriority%2Fblocker%2Cpriority%2Fcritical+-label%3Aneeds-ux-action%2Cneeds-ux-info%2Cstatus%2Fneeds-ux-approval%2Cui-ux%2Fin-design%2Cstatus%2Fux-approved+-project%3Ao3de%2F9) </td></tr>
       
<tr><td> Major </td><td> https://github.com/o3de/o3de/issues?q=is%3Aopen+label%3Asig%2Fui-ux+label%3Apriority%2Fmajor+-label%3Aneeds-ux-action%2Cneeds-ux-info%2Cstatus%2Fneeds-ux-approval%2Cui-ux%2Fin-design%2Cstatus%2Fux-approved+ </td></tr>
       
<tr><td> Project board </td><td> https://github.com/o3de/o3de/projects/10</td></tr>
       
<tr><td>(No priortiy) -Major, -Minor, -Critical, -Blocker </td><td> https://github.com/o3de/o3de/issues?q=is%3Aopen+label%3Asig%2Fui-ux+-label%3Apriority%2Fmajor%2Cpriority%2Fminor%2Cpriority%2Fcritical%2Cpriority%2Fblocker+-label%3Aneeds-ux-action%2Cneeds-ux-info%2Cstatus%2Fneeds-ux-approval%2Cui-ux%2Fin-design%2Cstatus%2Fux-approved+  </td></tr></table>
 

### Other queries:   
<table style="border:0px;">
<tr><td width="200px;">Full list </td><td> https://github.com/o3de/o3de/issues?q=is%3Aopen+label%3Asig%2Fui-ux+-label%3Aneeds-ux-action%2C+-label%3Aneeds-ux-info%2C+-label%3Astatus%2Fneeds-ux-approval%2C+-label%3Aui-ux%2Fin-design%2C+-label%3Astatus%2Fux-approved  </td></tr>

<tr><td width="200px;"> Global - is open and assigned to a designer </td><td> https://github.com/o3de/o3de/search?q=is%3Aopen+label%3Asig%2Fui-ux%2C+label%3Aneeds-ux-action+-assignee%3Abhanuja-s+-assignee%3Arainbj+-assignee%3Aamzn-leenguy+-assignee%3Ayuyihsu&type=issues </td></tr>
       
<tr><td width="200px;"> Bugs without priority </td><td> https://github.com/o3de/o3de/issues?q=is%3Aopen+is%3Aissue+label%3Asig%2Fui-ux+label%3Akind%2Fbug+-label%3Apriority%2Fcritical%2Cpriority%2Fblocker%2Cpriority%2Fmajor%2Cpriority%2Fminor+-label%3Aneeds-ux-action%2Cstatus%2Fneeds-ux-approval%2Cui-ux%2Fin-design+ </td></tr>

<tr><td width="200px;"> Blocker/Critical bugs </td><td> https://github.com/o3de/o3de/issues?q=is%3Aopen+is%3Aissue+label%3Asig%2Fui-ux+label%3Akind%2Fbug+label%3Apriority%2Fcritical%2Cpriority%2Fblocker+-label%3Aneeds-ux-action%2Cstatus%2Fneeds-ux-approval%2Cui-ux%2Fin-design+ </td></tr>
         
<tr><td width="200px;"> Major bugs </td><td> https://github.com/o3de/o3de/issues?q=is%3Aopen+is%3Aissue+label%3Asig%2Fui-ux+label%3Akind%2Fbug+label%3Apriority%2Fmajor+-label%3Aneeds-ux-action%2Cstatus%2Fneeds-ux-approval%2Cui-ux%2Fin-design+ </td></tr>
       
<tr><td width="200px;"> Needs-ux-action </td><td> https://github.com/o3de/o3de/issues?q=is%3Aopen+is%3Aissue+label%3Aneeds-ux-action </td></tr>
<tr><td width="200px;"> Ui-ux/in-design </td><td> https://github.com/o3de/o3de/issues?q=is%3Aopen+is%3Aissue+label%3Aui-ux%2Fin-design </td></tr>
<tr><td width="200px;">Tickets that need UX approval:</td><td> https://github.com/o3de/o3de/issues?q=is%3Aopen+is%3Aissue+label%3Astatus%2Fneeds-ux-approval </td></tr></table>


### Tags
* During this triage session this representative needs to make a few calls. Does the ticket we are looking at have a UX workflow that will affect the user’s visual understanding of O3DE in any way. If it does, one or more of the following tags should be applied. An additional tag beside Sig/ui-ux should be added to every ticket we process during triage.
    * **Sig/ui-ux**: This indicates there is some unspecified amount of work needed to be review by the UX team. This tag doesn’t give any specific details about complexity, approval needs or any specificity about time. This is a mere indicator that UX involvement is needed to some degree. This tag should only be removed by someone representing our UX group.
    * **needs-ux-info**: This tag is to be used when a ticket requires more information from a developer or the ticket creator to be able to make a call on what our next steps should be. At this point the UX representative is unable to determine next steps. 
    * **needs-ux-action**: We would add this tag in addition to the previous tags. So, someone has identified that this ticket cannot proceed without action being taken from the UX team. This will need a specific UX owner. Time for assigning owners will be allotted in the Sig-UI-UX triage session for this. However, owners can be added by anyone. This tag should only be removed by someone representing our UX group.
    * **status/needs-ux-approval**: This tag will be added to a ticket where there is some unspecified amount of changes that impact the workflow and or UI and it requires UX eyes before it can be delivered to production. This tag doesn’t mean UX is required to deliver mock or graphics for this ticket. However, it does require a UX person to give a sign off on the ticket that it doesn’t conflict with any known design patterns, upcoming work, or breaks any foundational patterns we have already established. This tag should only be removed by someone representing our UX group.
    * **ui-ux/in-design**: After a ticket has been assigned to a designer. The ticket should be marked ui-ux/in-design“ indicating this ticket is active and In progress by a design resource. This tag would be removed if the task is resolved or if the ticket is being moved out of the UX workstream. This ticket tag can be added and removed as many times as needed.
    * **status/ux-approved:** This tag is added to ticket who have UX final sign off for a ticket. This should not be added to a ticket until all UX actions are completed including, design, research, feedback. This ticket does not mean sign off is good from PM or SDM. This means from the UX point of view all task related to UX have hit the quality and clarity bar that we are ok with proceeding with this solution. This tag should only be added by the UX designer who owns this work. When marking approved on a ticket the user should also re-assign the ticket back to the developer or SDM who owns the workstream (if one is not already included). 
* Sometime it will be obvious and we can assign a feature label if known.
* if it needs UX action we need to go through the list a second time and assign specific owners to items that need action. If no UX owner this mean the item is pending triage ownership.
* If UX reviews a ticket and determine that ux is not needed we will remove our tag but also add a comment specifying please follow ux patterns, ok to proceed without ux. 
* When processing UX tickets either in Sig-UX-UI or Sig-Release meeting please keep in mind the following use cases that don’t get resolved by a tag.

### How would development and UX share a single ticket?
From an ownership perspective GitHub allows for more than one owner of a ticket. This means the ticket that have UX should have two assigned contributors. UX owners will not remove development resources. We will try to keep most details in the ticket comments. However, some documentation might be linked outside GitHub Including Figma designs or Qualtrics research data.

### Which team should own this ticket: Development or UX?
UX can be assigned as a co-owner from a team perspective. No single threaded ownership is required anymore. You can assign two teams.

### How is a ticket marked as “rejected” or “please fix“ if it’s just UX rejected?
If a ticket is rejected or asked for additional updates, we will change the status of the ticket to match its current state regardless of split deliverables. This means a ticket can be set as rejected with qualifiers but still be good from a code point of view. We imagine this might change as we learn more.

### When should we be removing any of the labels?
The primary time when we can remove label is when the ticket is marked “Status/ux-approved”. At that point you can remove “need-ux-action” and “ui-ux/in design”

### During our bi-weekly Sig-ui-ux charter meeting we will do the following actions:
* Review all the tickets labeled Sig/ui-ux ** that have not already been processed. (Open tickets only)
* Review any tickets we have recently closed that would be useful for the group to understand any major changes to the workflow.
* Identify any new patterns / icons that need to be added to our library or BlueJay design system documentation.
* Help unblock designers if they need clarification on next step or resources to reach out to. 
* Add team and specific UX owners to the tickets for processing.
* Assign which UX contact should be looked at the ticket (if one is known).
* Try to categorize the tickets into different buckets during triage. Completed, in-progress, not started, and backlog / rejected. 
   
### What's our plan for more community contribution?
* We have externalized all of our major design related activities so that the public can attend. This includes ticket triage, UX design review, Rev the engine updates, Blue Jay Design system reviews, and open office hours.
* The Sig-ui-ux team holds two standing meetings. This meeting meets every Wednesday but alternates discussion points based on week.
* These meetings are communicated on the O3DE calendar, O3DE UX mailing list, GitHub issues (mtg-agenda), and on discord before every meeting.
* For these meeting we will look for creative ideas of topic name to peak user interest (Example from JT: UX smacking. Test-drive Tuesday, etc.)
* Get the community involved in the conversation (if possible).
* Lurkers can often be our next best customer. So help them feel included but don’t be forceful with the conversations or topic. Let them lurk and join the conversation when ready.
* Don’t ghost the community.
* Make sure after a decision has been made in the public that you don’t forget to relay the outcome to the group.
* Do our best to answer question posted in the group as soon as possible. A lack of response can chase people away.
* We will help prioritize use case or problems effecting the expert. Then secondarily hobbyist and influencers. 
* Expert discussions: as we are working on specific topics of conversation, we plan on reaching out to different members of different game teams directly to give different demos or test a specific workflow. In these situations we might provide gift cards as a thank you for your time and energy. More details about the specific contribution will be made available as we have them.

### How do we make sure that community contribution is rewarded?
* First and foremost. Not all good ideas come from just us. So, we want to make sure we acknowledge the people who contribute good ideas. This is either in conversation amongst the group or writing shared amongst Sig-ui-UX group. Please note that this Sig-ui-ux group doesn’t have the power to make announcement on behalf of O3DE, but related to UX when we are given the floor, we intend to recognize your contribution. 
* Individual contributors have the option of earning different status among the UX team including Git privileges.
* An assigned UX designer on a ticket will note on that ticket any external contributions which helped. Based on the number of tickets this individual has been helpful in accomplishing he will be assigned a badge level. Badge level will indicate your status. 
     * **Beginner-level** - 0 to 5 tickets (5 tickets)
     * **Green-level** - 6 to 16 tickets (10 tickets)
     * **Mid-Level** - 17 - 32 tickets (15 tickets)
     * **Advanced-level** - 33 to 53 tickets (20 tickets)
     * **Staff** - 54 and above


###  Other ideas to raise customer engagement: 
* As a system we should work in close collaboration with 3rd party tools. These contributors will bring with them a ton of their own developers and users. So, supporting the smaller ecosystem will help make community contribution higher.
* When working on issues, try not refer to a “unspecific task name/number” instead refer to the customer problem we are looking at when announcing topics of conversation for meetings. This will attract people to very specific conversations that interest them. 
* Consider using some kind of voting system to allow people to participate who might not have the time to be vocal in their contributions. 
* Use a system called “Graphic-all” which allows user to download experimental builds with maybe two alternative UX workflows. People become invested in seeing their option do well.
* Pay attention to YouTube comments specific to UX and follow up with individuals that have something to say but maybe are not active contributors.
* Beware and have strict rules around people who want to get leadership abilities by paying for their badge system. The badges should be earned not paid for.
* Help promote learning tutorial videos and ask to be a contributor and or ask them to promote Sig-ux-ui group. 
* Go into all the social media and engage in the conversation on these other platforms. 
