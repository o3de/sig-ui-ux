# UX Charter - UX patterns for O3DE

This document outlines the process for submitting changes to the Open 3D Engine UX patterns or adding new features that are not fully covered in the existing pattern library. 

## What is required for a submission to be accepted?

* A new pattern can only be introduced when a new feature or an existing feature requires this feature work. Meaning it is not the responsibility of the SIG to keep track of patterns that are not being used inside O3DE.  
* It is required that all new patterns be validated against at least 3 game teams.  Minimum of 5 individuals. 
    * The details collected should be. Teams you validated against, type of research study, date, Questions asked, and % or number of candidates who agreed and disagreed with  your design,
    * These details should be submitted to the UX Sig along with your designs for approval (See form below).
* All new patterns must validate their design against the existing build. Verify these new patterns do not overlap with  existing patterns. 
    * If this new pattern does overlap with an existing pattern, you must relay this information during the review of your new design pattern.
    * It will be the responsibility of the UX sig to decide if these two patterns can work harmoniously, if the two patterns need to merge, or if they are incompatible with one another. 
        * If it’s decided that two patterns are incompatible with one another, the pattern is rejected.
        * If the pattern can merge or work harmoniously than the pattern can proceed to the next step. 
* If a new pattern is identified and should move forward, it must receive a up vote from the creator, the chairman and 51% of the contributors. 
    * If at any point the Sig cannot come to an agreement on their own. It is requested that the global arbitrator come in and help make a final decision.  The Chairman will help make the determination of the arbitration 
    * If the pattern is excepted. They must continue to the next step.
* A ticket needs to be created that will track all the activity, approvals and research and work being requested.
    * It is the responsibility of  the creator to identify all location in which this new pattern should be used and request this specific detail in the ticket.
* Documentation for the website: The number one detail needed is all of the specific use case(s) in which you would like for your patter to be implemented. Please note that you may not include any new pattern and or additional content that was not approved by the UX Sig.

## Enforcement and Review

* It is up to all of us to help enforce the standards of the UX Sig. If you identify a location where the UX pattern seems to be inconsistent with our pattern rules. Please report it to the [UX Sig mailing list](https://lists.o3de.org/g/sig-UI-UX), who will review this issue and make a determination on how to move forward. 
* During the submission of any new Gems or services back to O3DE we will be working closely with our QA team to confirm pattern accuracy. If a pattern conflicts with existing pattern or a new/modified pattern is uncovered during the review process, the code submission will be put on hold until the UX charter can review and sign off on this process.

## How do I request a UX pattern review? 

Please submit the below form to the [UX Sig mailing list](https://lists.o3de.org/g/sig-UI-UX) or file an issue in [o3de/sig-ui-ux](https://github.com/o3de/sig-ui-ux/issues) and we will put this item as an agenda item on our next meeting or resolve it through the issue comments. Depending on the complexity of the feature we may or may not request you to attend a meeting to go over the details of your request.

### What should be on the form I submit?

* Your name or GitHub username
* Your company (if applicable) 
* Description of your new pattern
* A written description of your use case(s).
* The problem you are trying to solve.
* Visual examples of the use cases.
* Identify all location in which this new pattern should be used.
* Does this pattern conflict with any other patterns (Yes; where?)
* Research details (see above)
* Implementation details involving the change 
  

