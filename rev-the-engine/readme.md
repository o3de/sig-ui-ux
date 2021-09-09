# Rev the Engine Program

Rev The Engine (RTE) is our program to measure and improve the user experience of a set of common CX workflows over time in O3DE. It consists of several steps: 1) we define a user workflow, 2) we test the workflow with a user (a process we call “Walk the Engine”), 3) we measure the quality of the workflow and report the bugs we find, 4) the community (including the team in AWS) submits fixes for the workflow, 5) repeat. This allows us to understand exactly how users interact with various parts of the engine, and what their expectations are. 

Amazon started RTE in early 2021, working on common “Day 1,” “Week 1,” and “Month 1” workflows. These are the workflows we’re focusing on:

* #### Day 1 workflow:

  * Workflow 1 - Onboarding: the process of building or installing the engine and creating, building, and modifying projects. 

* #### Week 1 workflow:
  * Workflow 2 - Gameplay: Adding gameplay to a project
  * Workflow 3 - Actor development: creating, updating, modifying actors, including animation
  * Workflow 4 - World building: building the environment and levels
  * Workflow 5 - Look development: shaders, materials, audio

* #### Month 1 workflow:
  * Workflow 6 - Multiplayer: Adding multiplayer elements to the game, networking
  * Workflow 7 - Team collaboration: working on a project with multiple contributors
  * Workflow 8 - Editor extension: the process of creating Gems to extend the functionality of the engine
  * Workflow 9 - Packaging & deployment: the process of packaging and sharing your project

Each of these workflows are broad and will look different depending on what project you are working on. Within each are various user stories; when running Walk the Engine sessions we will focus on specific user stories from each workflow.


## Measure the UX quality

To ensure we know where we are in terms of the UX quality in each workflow, we measure the workflows against the following measurement framework-

### System Usability Score: 

The System Usability Scale (SUS) is an industry standard to measure the usability of a product or service. It was created by John Brooke in 1986. In UX, SUS is always used in an online survey or after each usability testing session for users to fill in. The results of the survey will be calculated using a formula, and the formula will output a SUS score which would provide a reference to the team how good/bad the usability is in the product/service. See the chart below.

| SUS Score	| Adjective Rating |
| --- | --- |
| > 80.3	| Excellent |
| 68 - 80.3	| Good |
| 51-68	| Poor |
| < 51	| Awful |

### Time-on-task: 

We measure the time and completion rate it takes for users to interact with key, critical workflows for the first time, and how they progress throughout the time. This data will help us understand the quality of each workflow. The longer time users would use a workflow to accomplish a task, the lower performance the workflow has.

### Issues identified: 
Each of the usability issues identified from the workflow evaluations will be prioritized in Blocker, Critical, Major, etc. against the goals we setup for each milestone. It is suggested all the Blocker and Critical issues should be addressed by the end of each milestone, and we will evaluate the status of the workflow against how many issues are left unaddressed.

Based on the measurement framework above, the following rating system is defined:

* **Excellent (A)** - A new customer should be able to accomplish the identified workflow within a reasonable amount of time without the use of documentation or help from others. The SUS score should be above 80.3. All the blocker, critical and major issues identified through the evaluation are addressed.
*	**Good (B)** - A new customer should be able to accomplish the workflow with some help from documentation or instructions from others within a reasonable amount of time. The SUS score should be above 68. All the blocker and critical issues should be addressed.
*	**Passable (C)** - A new customer will need to read the documentation and follow instructions to learn how to perform certain tasks in the workflow, and they can confidently accomplish the workflow the second time within a reasonable amount of time and without any help of documentation. The SUS score should be above 51. All the blocker and critical issues should be addressed.
*	**Poor (D)** - A new customer isn’t able to accomplish the workflow easily due to blocker or critical issues, or it might take them extremely long hours to accomplish the workflow with workaround solutions. The SUS score is below 51.
*	**Failed (F)**- A new customer isn’t able to accomplish the workflow even after reading the documentation, and there’s no workaround solution.


## More about Rev the Engine Program

1. RTE Roadmap

## Join Us!

So, how can you help with RTE?

There are several opportunities for community members to participate in RTE:

* Participate in a “Walk the Engine”* session
     We are always looking for folks who are willing to walk the engine. These sessions are typically on camera and recorded, with an audience of AWS folks. This allows for the user to ask questions if they get stuck and to provide feedback as they work. Having a recording allows us to go back and follow the same steps to reproduce errors. It can be a bit intimidating, so remember that Walk the Engine is a test of the engine, not of you!
* Submit fixes and improvements
     We always have a backlog of bugs and issues stemming from RTE sessions. Please take a look at the backlog [here] and see if there’s anything you want to help with!
* Define new user stories and run Walk the Engine sessions
    Is there a workflow or user story you’re passionate about? Something you think needs extra attention? Work with the UX SIG to define and begin testing on it!

*Walk the Engine comes from the phrase “Walk the store,” a fundamental part of the retail UX experience where a designer would physically walk through the store to ensure that the shopper experience was as intended.*


