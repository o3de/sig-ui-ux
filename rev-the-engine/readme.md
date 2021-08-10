# Rev the Engine

Rev the Engine (RTE) is our program to evaluate and improve the user experience of workflows in O3DE. It consists of several steps: 1) we define a user workflow, 2) we test the workflow with a user (a process we call “Walk the Engine”), 3) we measure the quality of the workflow and report the bugs we find, 4) the community (including the team in AWS) submits fixes for the workflow, 5) repeat. This allows us to understand exactly how users interact with various parts of the engine, and what their expectations are. 
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

How long time it take users to interact with key, critical workflows for the first time, and throughout time? Each of the workflow should be completed within a reasonable amount of time. We will also use the competitive data as a reference.
 - Iteration time
 - Only a reference, not a hard bar
 - How much user can accomplish within an hour. rather than whether user can accomplish the task in an hour.

### Issues identified: 
Each of the usability issues identified from the workflow evaluations will be prioritized in Blocker, Critical, Major, etc. against the goals we setup for each milestone. It is suggested all the Blocker and Critical issues should be addressed by the end of each milestone, and we will evaluate the status of the workflow against how many issues are left unaddressed.

Based on the measurement framework above, the following rating system is defined:

* **Excellent (A)** - A new customer should be able to accomplish the identified workflow within a reasonable amount of time without the use of documentation or help from others. The SUS score should be above 80.3. All the blocker, critical and major issues identified through the evaluation are addressed.
*	**Good (B)** - A new customer should be able to accomplish the workflow with some help from documentation or instructions from others within a reasonable amount of time. The SUS score should be above 68. All the blocker and critical issues should be addressed.
*	**Passable (C)** - A new customer will need to read the documentation and follow instructions to learn how to perform certain tasks in the workflow, and they can confidently accomplish the workflow the second time within a reasonable amount of time and without any help of documentation. The SUS score should be above 51. All the blocker and critical issues should be addressed.
*	**Poor (D)** - A new customer isn’t able to accomplish the workflow easily due to blocker or critical issues, or it might take them extremely long hours to accomplish the workflow with workaround solutions. The SUS score is below 51.
*	**Failed (F)**- A new customer isn’t able to accomplish the workflow even after reading the documentation, and there’s no workaround solution.




## Goals for GA in 2021

For GA, we want to improve the user workflows such that an engine builder studio can evaluate the engine by building a simple game with a few tech artists in the team, and package and test the game on different platforms.

To that purpose, the user stories we are currently working on are:

### Workflow 2: Gameplay (Poor → Passable)

As a user, I am able to create simple game in O3DE, using the following elements in the engine:

- Asset pipeline- I am able to import some assets with multiple materials from DCC tools to O3DE and achieve what you see is what you get (WYSIWYG). I should also be also able to iterate smoothly between my DCC tools and O3DE.
- Control the actor- I am able to setup a simple actor and control it to move around in the scene. (Actor, Controller, Input, Camera, Script Canvas)
- Environment- I am able to setup a simple environment with obstacles. (Whitebox, Asset Pipeline, Mesh, Material, Lighting, etc.)
- Game logic- I am able to setup the simple game events that include interacting with the obstacles in the environment and triggering audio and particle events, while doing so, the UI will display a simple scoring system telling the player their progress. (Script Canvas, GameState, Physics, UI)


### Workflow 5: Look development (Poor → Passable)

- As a tech artist, I am able to iterate quickly on my art assets between the DCC tools and O3DE.
- Authoring in O3DE to make templates and share with other artists to use in their contents.

### Workflow 8: Editor extension (Failed → Passable)

- As an engineer, I am able to create a Gem to extend engine functionality. 

### Workflow 7: Team collaboration (Failed → Passable)

- As a user, I am able to easily onboard my team and start collaborating with them to build a project.
- Level authoring
- Asset sharing
- engine modification deployment

### Workflow 1: Onboarding (Poor → Good)

- As a user, I am able to download the O3DE installer and install O3DE from the installer. 
- As a user, I am able to create a new project, including selecting Gems, build the project, and open it in O3DE

### Workflow 9: Packaging and Deployment (Failed → Passable)

- As a user, I am able to deploy my project to window/mac/linux to test my project.
- As a user, I am able to share my project with someone else to play.



