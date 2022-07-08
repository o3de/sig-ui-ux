# UI-UX Intake Process

## Introduction

SIG UI-UX is responsible for the user experience in O3DE to ensure the product quality is high and meets user’s expectation. We offer the following support to the O3DE community currently-

1. **UX research**- If you are interested in gathering customer data to validate a direction, or you want to know how customers think about an existing features, we can help you determine the best research methods to collect the data you need, and may be able to conduct the research for you.
2. **UI/UX design**- we provide UI/UX design support for new feature development or existing feature improvements. 
3. **UI/UX review and approval**- if you already have a UI/UX solution in mind for the feature you are building, we will help review the solutions to make sure it meet the UX standard in O3DE so we can maintain the UX consistency and quality bar across O3DE.

In order to have UX resources assigned and prioritized to support the tasks above, we ask the O3DE community and all SIGs to follow this **UX Intake Process**. This will allow us to provide better support for the community, arrange the UX resource accordingly, and raise the quality of our UX deliverables.

## SIG Community Responsibility

### *Q1: What needs to be reviewed by the UX team / SIG-UI-UX?*

Any tickets that has a user facing element in it (e.g., user workflow, UI pages, UI/error messages, etc.), their solutions need to be reviewed and approved by SIG-UI-UX.

### *Q2: How do I get the UX team / SIG-UI-UX to review or work on my tickets?*

* **Step 1**, add “**SIG/UI-UX**” label to your GHI ticket if it has a user facing element in it.
* **Step 2**, answer the following questions to determine what help you need from the UX team / SIG-UI-UX.
    * If the ticket requires a UX solution before the dev team can work on it, add “**needs-UX-action**” label to the ticket, then move to Step 3.
      
      <img width="271" alt="image" src="https://user-images.githubusercontent.com/75449675/177916051-301352a3-35a0-4df4-adf2-d991d3f70c11.png">

    * If the team is able to propose a UX solution but needs SIG-UI-UX to review the solution before implementation, add “**needs-UX-review**” label to the ticket, then move to Step 3.

      <img width="270" alt="image" src="https://user-images.githubusercontent.com/75449675/177916182-5f491efd-4d27-4dff-9ed6-759c864cd288.png">


    * If the ticket is a pull request and requires SIG-UI-UX approval before releasing to the customers, answer the following question- have you reached out to SIG-UI-UX before the pull request is created?
        * If YES, move to Step 3.
        * If NO, go to "**Q6: What if I fail to involve SIG-UI-UX or involve SIG-UI-UX too late for my tickets?**"
* *Step 3*, if you need to SIG UI-UX’s help immediately, attend **SIG-UI-UX Office Hours on Thursday at 9am PST** to review your request with us (see **Q9** for how to sign up SIG-UI-UX Office Hours). Otherwise, we will respond offline to your request in 2-week’s time.

### *Q3: When should I send my UX request to the UX team / SIG-UI-UX?*

Depending on the size of the request, it would take us at least 1 sprint (we run 2-week sprint cycle) to work on a UX request. We recommend to send the request to us at least **2 sprints/4 weeks** ahead of your development schedule, so we will have enough turnaround time to cover design, review, and iteration work. 

### *Q4: What should I include in my ticket to SIG-UI-UX?*

We need as detailed information you can provide as possible for your request. O3DE GHI repository provides templates for feature request and bug report. Please follow the template to provide the info we need. In addition, we also ask for screenshots of the UI, videos of the process, and relevant customer data if you have any. This will help us understand your request better, and enable us to work on your request faster.

### *Q5: Do I have to attend SIG-UI-UX Office Hours to review my request? Can I do this offline?*

Yes, you can do this offline. We have weekly triage meeting on Thursday at 9am PST on Discord to determine if we will accept any UX requests. However, our response time will be much slower (up to 4 weeks) based on the priority of the ticket. If you need immediate attention from the UX team / SIG-UI-UX for your request, come to our Office Hours is your best option.

### *Q6: What if I fail to involve SIG-UI-UX or involve SIG-UI-UX too late for my tickets?*

We recommend involving SIG-UI-UX before you start any development work. Involving SIG-UI-UX late would result in late changes in your development cycle. This usually happens when the developed solution is ready to be released through a Pull Request on GHI, and SIG-UI-UX is involved in the last minute to review the pull request and find the solution isn’t meeting the standard or the quality bar. When this happens, *you will need to attend the SIG-UI-UX Office Hours to review the Pull Request with us in person.*

### *Q7: Can I still push the solution to Development without SIG UI/UX approval?*

Yes you can still push the solution to Development without SIG UI-UX approval. However, the solution should still be reviewed by SIG UI-UX even it’s been released. Please create a UX review ticket on GHI to review the solution with us as soon as you can. We want to ensure the solution is following the UX guidelines and is meeting the high quality bar to give user a consistent and effective experience.

### *Q8: How do I know the status of my UX request?*

Once we accept your request, we will assign your request to the “O3DE UX Roadmap” to the Project. We will update the status of the ticket through the Project status. You can also visit [O3DE UX Roadmap](https://github.com/o3de/o3de/projects/10) to see what SIG-UI-UX is working on.

<img width="314" alt="image" src="https://user-images.githubusercontent.com/75449675/177917004-5b9cd4d2-5459-4c49-a948-b8a9546046c1.png">

### *Q9: How do I sign up the SIG-UI-UX Office Hours?*

SIG-UI-UX Office Hours occurs every Thursday at 9am PST on Discord SIG-UI-UX voice channel. You can visit https://github.com/o3de/sig-ui-ux/issues to choose a time, and add your topic with the link to your ticket in the comment area. Then show up to our Office Hours at the time of your choice. 
