# 2022 Q2 O3DE User Survey

Last Updated: [2022-09-22]
Contributor(s): [amzn-yuyi](https://github.com/yuyihsu)

- [Introduction](#introduction)
- [Survey Findings](#survey-findings)
	- [Overview](#overview-of-the-satisfaction-confidence-and-efficiency-for-the-9-workflows)
	- [Detailed Workflow Analysis](#detailed-workflow-analysis)
		- [Analysis for Onboarding Experience](#1-analysis-for-onboarding-experience)
		- [Analysis for Experience Design](#2-analysis-for-experience-design)
		- [Analysis for Actor Development](#3-analysis-for-actor-development)
		- [Analysis for World Building](#4-analysis-for-world-building)
		- [Analysis for Look Development](#5-analysis-for-look-development)
		- [Analysis for Multiplayer](#6-analysis-for-multiplayer)
		- [Analysis for Team Collaboration](#7-analysis-for-team-collaboration)
		- [Analysis for Engine Extension](#8-analysis-for-engine-extension)
		- [Analysis for Packaging & Deployment](#9-analysis-for-packaging--deployment)
	- [Help System Satisfaction Analysis](#help-system-satisfaction-analysis)
	- [Ranking of the Feature Analysis](#ranking-of-the-feature-satisfaction)
- [General Demographics Analysis](#general-demographics-analysis)
- [What Action Did We Take After?](#what-action-did-we-take-after-this-survey)
- [What's Next?](#whats-next)


## Introduction

O3DE SIG UI-UX conducted a survey in June 2022. The goal of this survey is to help the O3DE community get good insights on what we’ve been doing right, and where else we should focus on to improve further in the future releases.

Considering O3DE has over 40 features used by various user roles in a game team, instead of asking survey respondents to give feedback to all 40+ features in one survey, we structured the 40+ features into 9 common game development workflows, and users were asked to provide their sentiments and feedback only to the workflows they have used in O3DE.

These 9 common game development workflows include:

1. **Onboarding Experience:** includes visiting O3DE website, downloading and installing O3DE, creating and building a project, customizing a project with gems, and launching the O3DE Editor to start building content for the first time.
    
2. **Experience Design:** includes bringing 3D assets to O3DE and managing them using Asset Browser, building game objects using entities, prefabs, and components; setting up game mechanics using physics, camera, input system, Script Canvas, UI Editor; and interacting with viewport and play mode to test the content they build.
    
3. **Actor Development:** includes importing and managing actor assets, building animgraph, motion events, ragdoll, hit detection, and cloth, and setting up the actor in the scene to interact with the environment.
    
4. **World Building:** includes setting up vegetation and landscape using dynamic vegetation system and landscape canvas, building terrain using the terrain system, and prototyping the world with the White Box Tool.
    
5. **Look Development:** includes setting up materials, textures, lighting, PostFX, etc. for a 3D model or a beautiful corner.
    
6. **Multiplayer:** includes setting up multiplayer content and networking for a game.
    
7. **Team Collaboration:** includes integrating with versioning control tools, setting up a project and its environment for the team to work together, onboarding team members, sharing and collaborating in the same files, etc.
    
8. **Engine Extension:** includes building new gems that contain new tool UIs, new components, new Script Canvas nodes, etc. to extend the engine capability to support various functions a project would need.
    
9. **Packaging & Development:** includes packaging the project files and test the projects on other platforms or share the projects with others for play test.

The survey was designed to answer the following questions-

-   Workflow satisfaction: How satisfied the user is with each of the 9 UX workflows
-   Workflow confidence: How confident the user feel they achieved the goal they set for each of the 9 UX workflows
-   Workflow efficiency: How efficient the user feel using each of the 9 UX workflows
-   Feature satisfaction: Within each of the workflows, how satisfied the user is with the features that form the workflow, and do they have any feedback for what they want to see us improve (with an open-ended question)
-   Demographic impact: How the user's role (e.g. Designer, Artist, Programmer, etc.) and years of experience with the game engines in the past impact their perspective of the nine workflows
    

#### Data Collection and Cleaning

The survey was distributed through the O3DE social channels on Discord, LinkedIn, Twitter, and FaceBook, and a reminder email was sent to the partners as well. The survey was opened from 5/20 to 6/15, for 3.5 weeks. The participants were screened to only answer questions about workflows that they had experience with. A total of 206 participants’ data was analyzed and compiled in this report. 

## Survey Findings
### Overview of the Satisfaction, Confidence, and Efficiency for the 9 workflows
![](https://lh4.googleusercontent.com/NnqET3hYrEBeKY8JErrARDEj072hLfOyvsbRi45tFuMKakyzRKer_ADxdg38fpJVKaiiSm6woLClucQIXrBRefhtFP6PCLeZfSsXK8nOeXlAVOT1aQI1kaVAacKrpnxE1pDrpYeO70s0lbFhN8kYs2D-7XYaxpFOlBHF8rN6MahiIQ5O5qsgdI7pOg)

All workflows received user experience ratings between 2 - 4 out of 5, which suggests that participants felt there was room for improvement across all 9 workflows. The two highest performing workflows were Onboarding and Look Development which suggests our plan to laser focus on improving these two workflows using a data-driven approach have had a positive impact, and it has enabled users to finish these workflows within a reasonable amount of time. Meanwhile, six workflows (i.e., Actor Development, World Building, Multiplayer, Team Collaboration, Engine Extension, Packaging and Deployment) received negative ratings (below 3 for all three ratings), which suggests that participants felt those workflows are in the greatest need of improvements.

Below is a breakdown of Satisfaction, Confidence, and Efficiency ratings across the 9 workflows-

![](https://lh4.googleusercontent.com/NmXJl3SWU4hyNkDALOKEL_JVDNFAHM_KzSaGcRHu-brUVmVoF01SiIc_z6PJegNXEu_gXgCFSytHcKvhVOVxX8gJo_AvjC1HUs7YBzOcnGDDYr7LTJotS40wgOCWRp_eAjsM0DoUz2NlElE_gGuMmkmJTughJWqJ0frqlG09aNn1ItAZ-ebkCOM5wg)

Among the nine workflows, four of them (i.e., Actor Development, World Building, Multiplayer, and Team Collaboration) have a significantly lower rating on Confidence, which suggests users don’t feel confident that they achieved their goals even after they were done with the workflows.

![](https://lh3.googleusercontent.com/V08mOxRY4ggocYQQzMvl4cnn08tY-liW-crs4s_Q10oDCDR6z6EcCD10hNZHmkiW0egErhjS0xevZPdiQ5TvGbntRN-q6qgMJItsGWd0Qfm3wfEXlM2WJEnZnxbumVRqZihvzD0gIf7OP6A-PdMcDUCBiTqh6li0rZDGK6ZrtOcYquMfMkGL7HWAMQ)

There was not a significant difference between average Satisfaction, Confidence, and Efficiency scores across the 9 workflows.

### Detailed Workflow Analysis
### 1. Analysis for Onboarding Experience
	Onboarding Experience includes visiting O3DE website, downloading and installing 	O3DE, creating and building a project, customizing a project with gems, and launching the O3DE Editor to start building content for the first time. 

![](https://lh6.googleusercontent.com/7ve-gJJvM0BiK5t2mFPdisMTZzJGBOmMBhZ6bebfCz9D3pL7ZWbqo8IkDGeAQfdiio-GikZ5MW-2Ji46hIAbwxyQyIzu810SG2mcWX1QNMZT8W_e12aiZytDQt0o20QKvL6fpmrV1iSo-PzZee6qvvJmKuoEGB40IrNwej7qhh59QdhPdHTB-Y9BNg)

-   A total of 43 people responded to this workflow.
-   51% of the users are satisfied with their onboarding experience, with an average of 3.42 satisfaction rate. When looking at each of the features in the workflow, most of them have a Satisfaction rate above 3.5, with a slightly lower rate for the help system
-   When asked what areas users would like to see us improve-
	-   **Improve docs quality** (mentioned: 20+):
		  
        “Documentation is often missing steps. Project vs Engine centric builds are not clearly covered.”
	-   **Improve Linux experience to be on par with the windows experience** (mentioned: ~15):
	    
        “Linux setup is complex and requires a lot of extra hoops. Hoped automation/scripts would help there but spent hours getting things setup.”
	-   **Improve Project Manager UI** (mentioned: 10):
	      
        “The program manager is good but needs more functionality... I would like to see Project Manager do more with the registration of objects.”
	-   **Make it easier to access external gems and projects** (mentioned: 10):
	    
        “There are no external gems or projects available by default and no easy way to find them online.”
	-   **Installation progress** (mentioned: 7):
	    
        “Implementing the better visualized progress bar (than [xxx/xxx]) or estimated building time when building the project via Project Manager could have a positive effect on first impressions.”

### 2. Analysis for Experience Design
	Experience Design includes building game objects using entities, prefabs, and components; setting up game mechanics using physics, camera, input system, Script Canvas, UI Editor, etc.; and interacting with asset browser, viewport, and play mode, etc.

![](https://lh3.googleusercontent.com/QCKe_CJ76X0hm8ZlsgwyjSe395oSG-aUyEJSLpT6dx5M95Wcwg2TqHn7h8sfq9LEEiEMr3fPpo4NuW0SDTrDUS6rDeZx-C6ffil4Pbp05MwzxUZi9co7vJFYZ0t1eUd0QjSYaXpp2gQKlGj0daBnvZ4EzHaX9f1H2AR6yOr8nTLNpVFwzP6TBO7QHQ)

-   A total of 79 people responded to this workflow.
-   The Satisfaction rate for Asset Browser, Physics, UI Editor, and the help system are particularly low (mostly below 2.8), compared to the rest of the features, which are all above 3.
-   When asked what areas they would like to see us improve further-
	-   **Documentation** (mentioned: 23):
		  
        “The document does not feel like it does a good job getting new users past the tutorial stage.”
		
        “Documentation...the real problem. To solve problems I have to look not only at documentation (as I do with other engines like unity or unreal AND also open source godot), but also search information on discord and examples.”
	-  **Physics** (mentioned: 8):
	    
        “I wish you could do a better job of designing the physics engine. I have encountered many unsolvable difficulties in the process of modeling.”
		  
        “Physics can be quite unintuitive when used in conjunction with scripting (especially when more advanced player/level movement is involved), mostly due to how collisions can behave on multiple different ways a movement can be implemented (Move Entity, Rotate Around <Axis>, Add Velocity, Apply Linear/Angular Impulse), and on what collider components (PhysX Character Controller, PhysX Shape Collider, PhysX Collider, White Box/White Box Collider).”
	-  **Script Canvas** (mentioned: 8)
	    
        “Mergeability of script canvas was an issue during game development.”
		
        “Was unable to expose AZ::Interface to script canvas.”
		
        “Using AZ::Event in Script canvas is really unintuitive in difference with EBus notifications.”
		
        “No Script Canvas events for Collisions for PhysX Character controller.”
		
        “Unstable and buggy”
		
        “Script Canvas is missing a couple of crucial functions i.e. working with files.”
		  
        “Lua scripting is far more enabling than Script Canvas, but it does not have a "full workflow guide" (e.g. the Pong tutorial on the official O3DE YouTube channel), only several sample scripts."
	-   **Editor UI** (mentioned: 7)
	    
        “Inspector labels get cut really often and values take a massive unneeded amount of space that could be used for the labels.”
		    
        “Using Mouse wheel on the entity inspector may change values inadveredly while scrolling.”
		
        “Parent/Child windows getting focus is still an issue.”
		
        “The UI needs to be redesigned. It's not pretty”
	-   **Asset Browser** (mentioned: 7):
	    
        “The asset browser needs an optional view mode that splits viewing the assets from the folder tree into two panels.”
	-   **Play mode** (mentioned: 4)
	    
        “modify entities and components while in Game Mode, this would allow the user to see how these changes impact the game without the need of restarting the game mode.”
	-   **UI Editor** (mentioned: 4)
	    
        “Use prefabs”
	    
        “Allow to animate objects”
		  
        “Unstable and buggy”
	-   **Tutorial** (mentioned: 4)
	    
        “More detailed tutorials about Gameplay Design tools on the documentation page or YouTube would be helpful.”
		
        “It would be useful to have a set of tutorials on how to create more advanced game mechanics in Script Canvas.'”
	-   **Input** (mentioned: 2)
	    
        “Creating input mappings is very tedious and the UX defaults are almost always wrong and must be changed.”
		
        “Having predefined inputs for standard controller types would be great.”
	-   **Lack of good sample or default settings** (mentioned: 3)
	    
        “There are no good starting player controller samples that have the correct physics, animation and camera setup.”
	-   **Entity/Prefabs** (mentioned: 3)
	    
        “An entity cannot start deactivated anymore.”
		
        “Spawn prefab Node outputs an entity list that contains also the Container entity. That could cause confusion for the user Suggestion: Separate container entity from the rest of entities.”
	-   **Provide presets** (mentioned: 3)
	    
        “There are no good starting player controller samples that have the correct physics, animation and camera setup.”
	-   **Performance** (mentioned: 2)
	    
        “Asset renderer is very slow and brings work to a halt.”
	-   **Linux** (mentioned: 2)
	    
        “The main problem for me here is the discrepancy between the Linux (Ubuntu) and Windows operating systems, while on Windows there are some issues, they do not affect basic workflows noticeably. On Linux the issues that are currently existing are far easier to encounter, and (while not the engine issue) the operating system itself handles poorly in case of an issue, which in turn makes the engine feel worse to use. For example, there is a bug where the cursor can disappear when cycling windows with Play Mode enabled (e.g. in the Multiplayer case where the Server/Editor windows both could be needed) - in that instance the cursor has to be restored most of the times by relogging, in which case, simple launching/relaunching of a play mode can become very tedious (make changes > play mode > cycle windows > no cursor > try to focus Editor to exit game mode > save progress > shortcut to bring up logout prompt > logout > relog > relaunch the Project Manager via Terminal > relaunch the project > repeat).”
	-   **Asset importing** (mentioned: 1)
	    
        “Importing files into the engine is a little too complicated, compared to other engines.”

### 3. Analysis for Actor Development
    Actor Development includes putting together actor assets, building animgraph, motion events, ragdoll, hit detection, cloth, etc.; and setting up the actor in the scene to interact with the environment.

![](https://lh5.googleusercontent.com/GjVYjv2X71RPYzq_v607VhRTy-LJjBibdGYLRCfQyyDaERddNACUHBqNwla4FqzQD4hOuRpL4wV0-8fzNfUGCf7dH5YKiWiS6Irt3KJnPot5mvmBRUk1EdEVqag3GCTljNulK8anBxHAzUrROOyKnyjlxE_4RTg1eJRydRFI2GuD2AwM__hZV_zEQg)

-   A total of 23 people responded to this workflow.    
-   The Satisfaction and Efficiency ratings for this workflow are both at 3.18, with a low Confidence rating at 2.66, meaning users don’t feel confident they accomplish their goal after they finished the workflow.    
-   The Satisfaction rate for the actor development related features are mostly around 3, except for two of the features: setting up physics settings (2.77), and the help system (2.79).  
-   When asked what areas they would like to see us improve-
	-   **Animgraph building** (mentioned: 4)
		
        “Building animation system is difficult for me. I’m not entirely sure if I did it right.”
	-   **Asset importing** (mentioned: 2)
		    
        “I'd like to be able to find the required documentation or tutorial about importing the Actor assets to the project in .fbx format from at least one free 3rd party DCC tool (e. g. Blender).”
	-   **Animated character samples** (mentioned: 2)
		
        “Alternatively creating a Gem with a couple of simple Actors and animations for that Actors also could positively affect the first impression of a new user.”
	-   Others
		    
        “Zooming with scroll wheel in animation editor is extremely sensitive.”

### 4. Analysis for World Building
	World Building includes setting up vegetation and landscape using dynamic vegetation system and landscape canvas, building terrain using the terrain system, and prototyping the world with the White Box Tool.

![](https://lh5.googleusercontent.com/5O3mqs8aTtEGy1QFsiP3UJTcWTNQQabjxU7C0HcZ7iow3Zb-clDgTPZ8GEi7lwKu7r2GYDYUwvNeJY6YNHheGOkTRTpCYa--BSulfD2kVRw9EC86ZOU3a6YttbkL24-1OJpu2d9j9H0sfWYfSh7Sfn8C7Pl01EpwCVMUtpnVjkd3mne3xOkp1EVXsw)

-   A total of 41 people responded to this workflow.
-   The Satisfaction rate for this workflow is at 2.9, with 36% of the users aren’t satisfied with the workflow. The Efficiency of the workflow is also low (2.57), with 56% of the users aren’t satisfied with it. The Confidence level for this workflow is significantly low (2.18), meaning that users don’t feel confident that they achieved their goal after they are done with the workflow.
-   When looking at the feature level, the Satisfaction rate is particularly low on Dynamic Vegetation system (2.82), Terrain system (2.75), and the help system (2.65).
-   When asked what areas they would like to see us improve-
	-  **Simplify the terrain/vegetation setup process** (mentioned: 10+)-
		
        “Adding the correct set of components and hooking them up correctly to get a functioning terrain or dynamic vegetation still seems fairly difficult.”
		
        “Landscape canvas does not allow to spawn vegetation over the desired area. Vegetation customization does not work.”
		
        “The Terrain generation and the way to use it, it's too complicated at this moment.”
	-   **Documentation** (mentioned: 5): 
        
        “Lack of documentation."
        
        “The documentation for Landscape Canvas tool could be more developed - A short tutorial that would explain the most important concepts.”
	-   **Whitebox tool** (mentioned: 5):
		
        “It took me a lot of time to understand the white box tool.”
		
        “The white box tool is useful, however it becomes very difficult to achieve meshes that are common like a room with a door or a window or stairs. It's easy to make a series of walls, but then to make holes in them for doors or windows - that seems impossible with the current tool unless you plan ahead very carefully.”
		
        “White Box Tool is somehow unintuitive. Saving created objects for later use and occasionally selecting vertices/edges in the Edit Mode are most problematic.”
	-   **Provide presets** (mentioned: 3):
	    
        “The current system is very advanced and we don't seem to have any shortcuts or presets to do the most common terrain or vegetation tasks.”
	-   **Performance and error prevention** (mentioned: 2):
		
        “once I start to really add enough components to get an affect I want, the system starts to become very slow and changes can have very large negative effects because you can easily create something your system cannot render or that takes forever to generate.”
	-   **Bugs or quality concerns** (mentioned: 2):
		
        “I think I can get most of the details right. But the jagged edges in some of the images make me feel uncomfortable.”
		    
        “I hope the terrain design can be improved. Because when I was testing, I often encountered mold wear problems.”

### 5. Analysis for Look Development
	Look Development includes setting up materials, textures, lighting, PostFX, etc. for a 3D model or a beautiful corner.

![](https://lh6.googleusercontent.com/kiCfY8gaIzx97LS5OCIJFaMJec_SIEF-pAyEt0IKXIHeABla8OwOaI9KJDOxfh15BY8SHn0cPs5iUIgaiO88ZI9smdGMvxkikYiu-fVzbqVhu_CmJcj9X_ycyXKLwg6AubquloiI3fhNrxJqqU5BSLZZGQ7hrONrIlwSeqyqSb23BnM2abvnM-VibA)

-   A total of 20 people responded to this workflow.  
-   The Satisfaction rate for WF5-Look Development is at 3.3, which is the second highest among all 9 workflows, only slightly lower than WF1 Onboarding Experience (3.42). The data also showed that 55% of the users are satisfied with the workflow.   
-   The feature satisfaction for material assignment workflow and lighting workflow are the highest (over 4) in the entire engine. 
-   The Satisfaction rate for the PostFX feature is the lowest (2.84) compared to the rest of the features in the workflow, with the help system the second lowest (2.95).   
-   When asked what areas they would like to see us improve-
	-   PostFX (mentioned: 4):
		
        “I was unable to figure out the PostFX layer system on my own, even knowing what it supported and how it was supposed to work. I tried blending between two look devs and couldn't get one to blend to the other.”
		
        “I had no idea what the "override" sections were on some PostFX components and why you would want to use those instead of the existing controls which looked like they set the very same things."
	-   Material (mentioned: 5):
		
        “Setting up materials/textures in the Material Editor feels good after spending some time learning it. PBR materials can be created intuitively when compared even to other tools (e.g. Blender). Models with predefined materials can have them replaced by new materials made in O3DE.”
	-   Lighting (mentioned: 3):
		
        “Lighting a level with outdoor and indoor lighting is very tricky, especially if it involves a 24hr day cycle. I still don't know the correct way to use the ray-traced probe grid with large outdoor areas so I get ambient lighting kilometers away, and still have the correct precision for indoor areas.”

### 6. Analysis for Multiplayer
	Multiplayer includes setting up multiplayer content and networking for a game.

![](https://lh3.googleusercontent.com/t2BQK8JW0MY2yDliS44yYRgD8mYgZ1StFKgHEeudYc30yF2AHwDJdjxlg7FdgVG-0hrmhj1WuOfjVGGGpFTE3zEguWSAqvuWMp5ro9WTvHbhiL_MnxK23ffIB8zUOCwIqm1vY1W5VvrE6cc8OOQNnzgYP-FkCVCQ6rZSxdm9T9eXHWJxIhzTeEStjw)

-   A total of 28 people responded to this workflow.
-   The Satisfaction rate for WF6-Multiplayer is the lowest (2.48) of the 9 workflows. Over 58% of the users aren’t satisfied with their experience using this workflow. Their Confidence level to accomplish the workflow is also at the lowest (1.72) among the 9 workflows. 
-   The Satisfaction rate of the feature set is all below 3, with “configuring and adding multiplayer to a project” the lowest (2.48), followed by the “help systems'' (2.53).
-   When asked what areas they would like to see us improve
	-   **The barrier to entry for networking setup is too high** (mentioned: 6):
	    
        “The proper steps to set up a Multiplayer Project are still somewhat unknown to me. I used the AutomatedTesting project to test some multiplayer aspects and when I was playing the game in the editor, it would stop updating because the dedicated server would open and steal focus from the editor. At the time you also had to know a special cvar to set the player prefab to spawn which seemed very obscure.
		
        “Setup of Multiplayer Gem in new projects is quite complicated when compared to all other Gems (setting up the AutoGen, with some additional custom components), and testing/using it requires extensive engine knowledge to begin.”
	-   **Provide presets** (mentioned: 3):
	    
        “We need a multiplayer project template and multiplayer player controller samples to speed up the setup process.”
	-   **More tutorials** (mentioned: 2):
	    
        “Latest Multiplayer tutorial (2-part currently) on the O3DE YouTube channel is very good, it was very interesting for me to see how the developers themselves interpret and solve errors related to building/using projects, and it gave me quite few ideas overall even for "regular" workflows. After following it all through, and then repeating certain steps a few more times, I feel quite confident in recreating the Multiplayer Gem setup "from memory", even though it is quite complex workflow. I would love to see more of this tutorial series explaining the components used in the MultiplayerSample project thoroughly, and perhaps some more advanced game setup (e.g. Pong)."
	-   **Linux** (mentioned: 1):
	    
        “Multiplayer workflow on Linux itself feels very tedious, whenever any larger issue occurs, when both the engine and the operating system are taken into account.”

### 7. Analysis for Team Collaboration
	Team Collaboration includes integrating with versioning control tools, setting up a project and its environment for the team to work together, onboarding team members, sharing and collaborating in the same files, etc.

![](https://lh4.googleusercontent.com/hyme5Egji4BIqhNf3V9vfOjLc63mTy6WF51jVjhNZKR1TRLIEXuxb0Z5n0Mzo1scEhCg_XMfq6lvu_lsm_2CPf0pVimE-csDHCICoFFetzvo9ss7x4l7mgSwFRz3dRgQUEdUR5-zGKj5wPEbauWGECK8C2x7F03P16CBzdJjt9KQzh0X5DyK2Wa5wQ)

-   A total of 23 people responded to this workflow.    
-   The Satisfaction and Efficiency for the workflow is at 3.0. However, the Confidence rating for the workflow is slightly lower (2.7).
-   On the feature side, users are looking for easier integration with the version control tools and clearer help system. Both of them are at 2.6 Satisfaction rate.
-   When asked what areas they would like to see us improve-
	-   **Support Git** (mentioned: 3)-
	    
        “The editor does not support git. GitHub's LFS service supports file locking which could be used in place of Perforce to help prevent team members overwriting binary files that are hard to merge.”
	-   **Lack of documentation** (mentioned: 3)-
		
        “I didn't find any simple guides on setting up a project in Perforce or Git that included everything a team would need.”
	-   **Team onboarding support** (mentioned: 1)-
		
        “As part of the distributed store-like functionality, a game team should be able to put a game project and game objects up on a private git repo and onboard a team member. I'd like to see that flow and possibly automate some of it through the program manager.”

### 8. Analysis for Engine Extension
	Engine Extension includes building new gems that contain new tool UIs, new components, new Script Canvas nodes, etc. to extend the engine capability to support various functions a project would need.

![](https://lh5.googleusercontent.com/6-oIgTGpbUmhYs-QElUnnJoYBUWlGc6N63T_dtwJuNZrg4MHIuoPAMg63NJhALM_DedZIbIM_I-BjimXG3oC-QI5fe0YFgpAh4T3kFyavgh6PUmolYO-wXRWqUIKeGNEhOh1RCc_orNxrwbGaPrjafXSH27i2TUY42f6APrG_ZC2QT8YAbu48VhzwA)

-   A total of 35 people responded to this workflow.    
-   The Satisfaction and Efficiency ratings are around 3, with a slightly lower confidence level (2.71) for this workflow.    
-   When asked what areas they would like to see us improve-
	-   **Documentation** (mentioned: 2)
		
        “Hope to add more search functions, so it’s easier to find the help I need.
	-   **Simplify the component creation process** (mentioned: 1):
		
        “Adding a component, especially if you use the atom defaults now typically means you have to create 7+ files and need to be added to different projects. <editorcomponent.h editorcomponent.cpp component.h component.cpp componentcontroller.h componentcontroller.cpp componentconfig.h> And many of these files need to be added to different projects. This is over-designing IMHO and significant friction to doing something that should be simple. Users should start with a simple 2 file setup until they get to the point where they have a good reason to split out into multiple files, and we should have a tool that quickly does all this for them, no hand creating and editing all these files!This is over-designing and friction.”

### 9. Analysis for Packaging & Deployment
	Packaging & Deployment includes packaging the project files and test the projects on other platforms or share the projects with others for play test.

![](https://lh6.googleusercontent.com/vXYN7nKyQf1Jiv837Qt0mK9YP3pGTFyyI4pQ8LwQLGnzx_N2RK7rNsGRe2b0jcM7rJIUOa2PoAOV-Aks_26OeKVe4akCikuPrXUtrEfZ5cjPPLHzXK_dNGZ2X0aPnv7yVXKqqF5Jnl9ywjLfd3hsMKzgczm6teCNLVpp3HfdsmFunDkPTgir7CKdPQ)

-   A total of 31 people responded to this workflow.   
-   The Satisfaction rate for this workflow is the second lowest (2.73) of all 9 workflows, which is slightly higher than WF6-Multiplayer (2.48).    
-   When asked what areas they would like to see us improve further-
	-   **Lack or out of date documentation** (mentioned: +10):
	    
        “There is no documentation with clear steps on how to make a release build package. In addition the pages explaining how to make a bundle are out of date and do not represent the current status of the feature, which leads to time spent in something that doesn't work. It would have been preferable to not have documentation rather than incorrect documentation: [﻿https://o3de.org/docs/user-guide/packaging/asset-bundler/﻿](https://o3de.org/docs/user-guide/packaging/asset-bundler/) These page also include broken links.”
	-   **1-click automation asset bundling process** (mentioned: 3):
		
        “Most users just getting started are not going to have complicated setups and even if we just had an option to include all assets in the user's game project folder they should still get a result that is way better than the 1GB package default which just zips up the entire cache folder.”
		
        “It should be much easier. In the perfect world, the User after clicking the button, all necessary files are copied to the output folder or the release is being created.”
	-   **Asset Bundler Gem should be built by default** (mentioned: 2) 
	-   **Deployment should be streamlined and automated** (mentioned: 5):
		
        “Deployment on other platforms is slow, complicated and tedious. This should be automated.”
	-   **Support Linux** (mentioned: 2):
	    
        “Not being implemented on Linux, and not working on installer "out of the box" can also add to mentioned confusion."

### Help System Satisfaction Analysis

When the workflow isn't intuitive enough to guide users to achieve their goal, users will seek documentation or tutorials for help. If they can't find the answer they are looking for, they will become frustrated and might end up dropping out of the product. In O3DE, the Satisfaction rate of the help system for the 9 workflows are all below 3, with exception on WF1 Onboarding Experience, which is 3.1. When looking into the data, we found that over 50% of the users were not satisfied with the help system in 5 of the workflows (WF2-Game play design, WF4-World Building, WF6-Multiplayer, WF7-Team Collaboration, and WF9-Packaging & Deployment). We also see a correlation between the intuitiveness of the workflow and the demand of the help system. The harder the workflow is for the user to use, the higher the dissatisfaction of the help system that users would rate. In addition to improving the help system, we should see this as a signal to further improve the ease of use of the workflow so users can depend less on the help system.

The current issues with our documentations can be summarized as below-
1.  Confusing site information architecture (IA).
2.  Lack of use case oriented content (e.g. tutorials).
3.  Inaccurate information provided.

|**Workflow**| **User Satisfaction of the Help System** | **User Satisfaction of the Workflow** 
|--|--|--|
| WF9: Packaging & deployment | 2.52 | 2.7 
|WF6: Multiplayer|2.53|2.4
|WF7: Team collaboration|2.55|3
|WF2: Game play design|2.64|3.2
|WF4: World building|2.65|2.9
|WF3: Actor development|2.79|3.2
|WF8: Engine extension|2.83|3
|WF5: Look development|2.95|3.3
|WF1: Onboarding experience|3.2|3.6

### Ranking of the Feature Satisfaction

Below is the rank of the features based on user’s satisfaction, sorted by the lowest to the highest satisfaction. It is suggested we should prioritize these features to improve in the upcoming O3DE releases.

Table sorted by User Satisfaction from lowest to highest.

| Feature Name | User Satisfaction | Workflow
|--|--|--|
| Configure/add multiplayer to a project | 2.48 | Multiplayer
| Setup networked component in C++ | 2.55 | Multiplayer
| Integrate with version control tools | 2.58 | Team collaboration
| Setup networked component in Script Canvas | 2.63 | Multiplayer
| Debugging tools for network issues | 2.7 | Multiplayer
| Play in editor experience | 2.72 | Multiplayer
| Terrain | 2.75 | World building
| Actor physics (ragdoll, hit detection, etc.) | 2.77 | Actor development
| Add/work with network component in Editor | 2.79 | Multiplayer
| Package files using asset bundler | 2.79 | Packaging & deployment
| Dynamic vegetation | 2.82 | World building
| PostFX | 2.84 | Look development
| Physics | 2.88 | Experience design
| Asset Browser | 2.89 | Experience design
| Import/setup actor assets | 2.92 | Actor development
| UI Editor | 2.95 | Experience design
| Onboarding team members | 2.96 | Team collaboration
| Build a new component | 2.97 | Engine extension
| Animgraph | 3 | Actor development
| Landscape canvas | 3 | World building
| Collaborate on the same files | 3 | Team collaboration
| Build a new tool UI | 3.1 | Engine extension
| White Box | 3.14 | World building
| Build a new SC node | 3.16 | Engine extension
| Actor interaction with the scene | 3.18 | Actor development
| Build a new gem | 3.18 | Engine extension
| Manage motions and motionsets | 3.27 | Actor development
| Build with game objects (entities & prefabs)| 3.33 | Experience design
| Viewport | 3.36 | Experience design
| Motion events | 3.37 | Actor development
| Inputs | 3.39 | Experience design
| Game mode | 3.39 | Experience design
| Script Canvas | 3.53 | Experience design
| Material editor | 3.53 | Look development
| Camera | 3.54 | Experience design
| Add & manage components | 3.58 | Experience design
| DCC tools integration experience | 3.64 | Look development
| Setup 3D models | 3.65 | Look development
| Install engine from GHI repo | 3.74 | Onboarding
| Create and build project | 3.74 | Onboarding
| Launch O3DE for the first time | 3.86 | Onboarding
| Customize project with gems | 3.88 | Onboarding
| Install engine using installer | 3.9 | Onboarding
| Lighting | 4 | Look development
| Material components & instance editor | 4.11 | Look development

## General Demographics Analysis

### Countries of the survey respondents

![Where are you located_.png](https://lh4.googleusercontent.com/TrLu9ZcMeLAA_Q23feND5S0j26LwR9h7UFuN7XASvMnY-n4GmDYe_4-5lwAVYw1gRRX2Dg-vSK7XCxl60c3T0I2rBVNB8bHTlCwHzVqJCi1c1vj0ZscFTXDWTGznCQAP65W-Aer30gZbx5zsjwh6mE82ApthUNisN9pPMebh14PCyvKlhUuGpGgSgA)

### Stages of using O3DE

![What is your current stage of using O3DE_.png](https://lh3.googleusercontent.com/DDLhPDU3Ex4IOAOmx7xdsqUhtIBoLQ5MjcbhRpKjFpzuaGx_nWJRPgitn3hZnubdu9cxm9LWwgZGAeK4Ajz7hBXnnQPBo3CDZq3peXLVcL32Tgoo8Pu3oGg7ShX1n1pJnyO_y60SFS7Oti9MJLmqFgvB0uyuqVfLNWYGSL-1ywbe4EJa3BpaFE-4bg)

### Roles in the game project

![What best describes your role in using O3DE_.png](https://lh5.googleusercontent.com/_HvMWwibowD4d7_-Si1rr0ykkc6L8dafqVfxkwdRBo-ebjknZ50uFfl8ohKy5MRqNppifqRZBfmu-oHBinrVPhBJ9V_OgBP0QCZ_6n6pN2Nl7LiLSlqBDXTd-KoiybgRuyZ3PpxhDqGqsAcKwzjXIUGWNiLST-erjd9JMbTSqJ4Dh7pmNje0K7zkJg)

### Years of experience using game engines

![How many years of experience do you have with game engines_.png](https://lh3.googleusercontent.com/vYGj721EC75wou5IfnG9BAs_ObYt9BDik2MlkvZ4TtzMsl0i_rV1M3MIGh870mob67VUy2-euFFhqbqgLtm5OplfVKHoSCdYAoYob_DSwsK87bYJ17XX9U_4x5QJqtp7afnRAXH5JAIMO3nUCZquNo6tHU0TYQ7e7mQXHSrf8uCGEov3XaN6XGIdXg)

When comparing the data between the years of experience vs. user satisfaction on the workflow, we don’t see a strong correlation to show that the less experienced users are with O3DE, the more dissatisfied they are.

### Working as a team or solo

![Are you working as a team or flying solo_.png](https://lh4.googleusercontent.com/CXR2No1ug3X4Og204YuVDUy76MCZgKp35avUZt9xpBNI5P6B-LTm7ZkUy7YT2PzpnWndLimxlwXFrSkGnACDk93PPxu27b1VBtBTnb-qTEg_kjMVJRKLS_jqo4mbNTa-Hrf_0WvqVBqclWFP5qcvhDLXG3U7bYQHOheGbR6hATbT8E_tNxrAdIMLdw)

  
  

## What Action Did We Take After This Survey?

While the survey data can tell us how users feel about O3DE, we need a deeper understanding of the contexts of what caused users to select ‘Dissatisfied’ in certain tools or workflows. In June-August timeframe, we invited around 20 community members and conducted a series of Walk the Engine sessions while focused on the 5 common workflows users employ when building their content with O3DE: Onboarding Experience, Actor Development, Look Development, Multiplayer, and Engine Extension.

We were able to identify 138 issues, including feature requests and bugs, that either block or impact users from accomplishing their tasks. By using the quantitative data to hone it on opportunity areas, and using qualitative data to understand these areas more clearly, we were able to work with each SIG to improve the workflows with clarity and priority. You can find the issues tracked on the GitHub [2022 Walk the Engine Issue Dashboard](https://github.com/o3de/o3de/projects/15).
## What’s Next?

A development branch with the critical issues we identified fixed will be released in late October, and we will conduct another round of O3DE Survey and Walk The Engine research using this branch in November and December timeframe to verify if the improvements meet user’s expectations.

If you are interested in improving the user experience in O3DE with us, you have two ways to contribute. You can provide your feedback by filling out the Survey and participating in our Walk the Engine research in November. Or you can pick up the issues that are most relevant to you from the [Walk the Engine Issue Dashboard](https://github.com/o3de/o3de/projects/15) and work on the solutions.

Please reach out to SIG UI-UX for more details.
