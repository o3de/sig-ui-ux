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
  * Workflow 10 - Cloud services integration: the process to integrate other 3rd party cloud services, such as AWS, with your project.

Each of these workflows are broad and will look different depending on what project you are working on. Within each are various user stories; when running Walk the Engine sessions we will focus on specific user stories from each workflow.


## Measure the UX quality

To ensure we know where we are in terms of the UX quality in each workflow, we measure each of the workflows based on the following measurement framework. The assessments are conducted through two approaches:
1. Bi-quaterly survey
2. Bi-quaterly walk the engine user studies

| CX Health Score | Workflow Completion Rate | User Satisfaction (1-5) | Workflow Efficiency / Learning Curve | 
| --- | --- | --- | --- |
| Excellent | High (>78%): Able to complete the workflow within the expected time.  | 5 | Efficiency High / Learning curve LowI can easily get started with the workflow without any help. When I need to work on advanced scenarios, there are sufficient docs/tutorials to assist me. The amount of time to complete and master the workflow exceeds my expectation. |
| Good | Mid-High (65-78%): Able to complete the workflow within the expected time. | 4 | Efficiency Mid / Learning curve LowI can easily get started with the workflow without any help. When I need to work on advanced scenarios, there are sufficient docs/tutorials to assist me. I can easily master the workflow, and the amount time to complete and master the workflow is meeting my expectation. |
| Passable | Mid: (45-65%) Able to complete the workflow but the progress is slow. | 3 | Efficiency Low-Mid / Learning curve MidI need some help to get started and complete the workflow. There are sufficient docs/tutorial to assist me when I need help. The amount of time to complete and master the workflow is longer than I expected but is acceptable. |
| Poor | Low (25-45%): Difficult to complete the workflow. | 2 | Efficiency Low / Learning curve HighI need a lot of help to get started and complete the workflow. There is no sufficient docs/tutorials to assist me, and the process is extremely long. Even I follow the docs/tutorials to finish the workflow in the first time, I might still not be able to complete the workflow on my own the next time. |
| Failed | Blocked (<25%): Unable to complete the workflow. | 1 | Efficiency Blocked / Learning curve HighI am unable to complete the workflow. There is no docs or tutorials to assist me, and there's no workaround solutions. |


## Rev the Engine goal and scope for 2022

https://docs.google.com/spreadsheets/d/1vxxpp2g0li90JocEHcvUJobnwx2p1IQxQJFd23KguHE/edit#gid=54683120

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


