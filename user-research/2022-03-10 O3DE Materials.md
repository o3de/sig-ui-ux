# O3DE Materials' Report

**Research Study:** Materials' Workspace Research Study  
**Last Updated:**   10 March 2022  
**Contributor:** [bhanuja-s](https://github.com/bhanuja-s)

- [Problem Statement](#problem-statement)
- [Methodology](#methodology)
  - [Research Objectives](#research-objectives)
  - [Research Questions](#research-questions)
  - [Participants](#participants)
- [Research Insights](#research-insights)
  - [Unifying Materials’](#unifying-materials)
  - [Custom Mesh](#custom-mesh)
  - [Source vs Instance Editor](#source-vs-instance-editor)
  - [Material Canvas](#material-canvas)
- [Next Steps](#next-steps)

## Problem Statement
The cohesion of the Render, Physics and Blast materials’ editing workflows is a complex process which requires a consideration into the *user experience*, *business goals*, and *technical feasibilities*.  

Currently, when users want to author Physics or Blast materials, they have to use different workflows and tools from Render materials. This is unacceptable because this makes it hard for users to constantly switch between contexts, and due to the increased iteration time when modifying the different material types. We envision a solution where the system enables users to author different materials in a consistent manner, without having to learn differing workflows and tools.

## Methodology
### Research Objectives
To understand the users’ learning journey while using the different materials, and to validate their preference on the unified Material Editor.

### Research Questions
1. Do the users want to author different materials simultaneously?
2. Do the users want to keep the materials’ workflows separate?
3. Would they want to unify the different materials’ workspaces?
4. What would they like to see in the viewport while editing the different materials?

### Participants
We spoke to **3** users: 
- Participant A is a Programmer Writer
- Participant B is an Art Director
- Participant C is a Lead Tech Programmer

## Research Insights
### Unifying Materials'
Users are either indifferent, or opposed to the unification of different material types

> “I wouldn’t say I like the current Asset Editor, but it is service-able.
> I‘d like something better, but I don’t see a practical upside to the effort it’s going to take to incorporate Physics and Blast into the Editor”
> — Participant A

> “We don’t have different Physics materials that do different things, we have one.
> We’ve been trying to get out of that...so we use a simple primitive box or cylinder because it’s much cheaper.
> We don’t pay too much attention to the Physics materials.”
> — Participant B

#### UX Recommendation
We suggest, as a short-term solution, implementing a Physics Editor which allows users to select, edit, manage, and/or create Physics materials directly within the editor.

This proposal includes discontinuing Physics material libraries, emulating the same paradigm as Render materials, while drawing away from the use of the Asset Editor.

![O3DE-Materials-01](https://user-images.githubusercontent.com/84036086/168581150-7504a20c-73d7-47ff-bdef-f89e84cf0b8a.gif)

### Custom Mesh
Users want to add a mesh of their choice in the Editor

> “Currently, I can put my own mesh in Material Editor and I can open multiple materials, but it gets assigned to the entire mesh.
> Allow me to minimally view a mesh with multiple, properly assigned materials in the Editor.”
> — Participant A

> “It’s super frustrating as its (Material Editor) a separate program, you don’t get immediate feedback.
> It’s very disconnected. Anytime I do any little thing, I see it in the 3D viewport.
> I don’t use the preview really, and to load up a separate model is a lot of work and it’s not the model in my level.
> So, it’s a frustrating way to work.”
> — Participant B

> “You can’t display the mesh of choice, and because of that you can’t set up the material properties (accurately) without the current mesh.
> We can’t see if things are working.”
> — Participant C

#### UX Recommendation
We want to surface the Model Settings hidden within the Viewport Settings directly within the Toolbar. This is a straightforward method to allow users to use their own models along with the given primitives.

Additionally, we think that the Model Preset Browser should be the default method of viewing a model, rather than in a stowed dialog within Model Settings. We are proposing a short-term solution of a model panel, which allows users to click and view their material on different models efficiently.

![O3DE-Materials-02](https://user-images.githubusercontent.com/84036086/168589084-830fe298-1f3f-4f74-b167-ba1df1625d04.gif) | ![O3DE-Materials-03](https://user-images.githubusercontent.com/84036086/168589472-73bed9af-748a-4887-b03a-f6cc67d1d8a5.gif)
--- | --- 

### Source vs Instance Editor
Users know the difference between Source and Instance Editor, but the true value of the Instance Editor isn’t shared

> “The source material is the material on disk - the base, and the instance is the one that is applied to the sphere.”
> — Participant A

> “I don't know. This is just the instance of the default material, you're just editing it's instance. 
> I think I understand the reasoning behind it. You probably go into the original source, open up the material editor if you really want to dig in and set up your main material.
> Then, if you have lots of different versions of it, or you just want to change something within a level you can change something on top of that.
> It adds a layer of complexity, I think a lot of people will get confused.”
> — Participant B

> “Usually for the Material Instance, you don’t really need it because you’re already in the level right? You already have a prefab to display.
> So, I don’t think it’s really useful. We use the Instance editor directly from the code.
> We have empty levels, and everything is populated at run time.”
> — Participant C

#### UX Recommendation
Currently, we have a Hamburger menu which stows away valuable user actions. We want introduce buttons which make these actions visible to the users.

There is an opportunity to reinvent the Instance Editor, by providing users with visual feedback on overridden properties, allowing them to lock the option of saving to source, and simply renaming this editor.

### Material Canvas
We asked users for their feedback on adding a Material Canvas to the current Material Editor. They are interested in a visual scripting environment for Material Editor.

> “I would like to see it as one application...the more you simplify the better, and the more I can work on one application the better, and the more you can merge everything into a cohesive system the better.”
> — Participant B

> “It’s cool, and of all the things that O3DE is working towards, this is the most exciting. It’s like Script Canvas, it makes a lot of sense”
> — Participant C

![O3DE-Materials-04](https://user-images.githubusercontent.com/84036086/168590886-cf75ae93-20d0-48c8-a638-578abd1124a0.gif)

## Next Steps
- There are a lot of unanswered questions regarding the Physics and Blast flows, and we will be contacting more customers to participate in our research studies. We hope learn more about the particular opportunities and frustrations from those who actively use the Physics and Blast editing workflows.
- It is also logical to work on detailed workflows, and test them with users for Material Canvas. This would support the initial proposal as shown [here](#material-canvas).
