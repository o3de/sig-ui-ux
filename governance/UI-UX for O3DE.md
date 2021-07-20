# UI/UX for Open 3D Engine

Welcome O3DE contributors! If you are reading this document,it's likely because of one of two reasons: 

1. You are building or modifying a front end feature of O3DE that has some kind of UI 
2. You are contributing to our UX/UI patterns and libraries that you want globalized 

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

## Future Additions to this guide

* What things can I do on my own?
* Whats falls outside of this plan?
* Approval process for content to go live
* What do I do if I don't have an answer to my question?
* Where are the resources located?
* What happens if I choose to ignore this 

