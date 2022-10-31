# UI-UX SIG - 7/29/2021

Facilitator: AMZN_Joshua, AMZN_yuyi

Meeting Notes: AMZN-Liv

## Agenda
https://github.com/o3de/sig-ui-ux/issues/22

## Attendees
AMZN_Joshua, AMZN_yuyi, daimini[Amazon], Liv [AWS], AMZN_Lee, WashedUp. New Doc, Sergio Rojas, JT[SCB_GameDesign], Pinfel, Niklas [Epos Studios]


## UI/UX Review Process (AMZN_Joshua)

- Planning to move to meet fortnightly (every two weeks)
- Will start hosting UI/UX drop-in office hours for community members. You can also schedule time slots. AMZN_Lee will be setting these up. Goal is to keep in touch and have access to the UI-UX SIG maintainers. 
- As development on the engine ramps up, the UI-UX SIG will be triaging and weighing in on the  design. 
- Triage meetings will be held weekly to review new issues 
- There will be new bi-weekly/fortnightly sprint review and sprint planning meetings for the SIG. This will be the meeting where the UI-UX SIG shares what they are proposing and working on 

Would love feedback on our UI/UX review process

### GitHub contribution processes
There are times where contributors will be making decisions about how a design should be implemented; it's important to loop in the UI/UX SIG for new user flows and user interface updates. If you see something on GitHub that has a UX element to it and the UI/UX SIG isn't involved, please surface it! 

### Triage process
On Mondays, issues in O3DE/o3de are triaged and assigned to SIGs for further triage. The UI/UX SIG will host a smaller triage specifically for issues tagged for UI/UX and will either a) share that the ticket doesn't need UI/UX approvale, b) Ticket does need UI support and should be blocked until signed off by UI/UX, c) approve the ticket as-is, or d) reject the issue's proposal. 

## Rev the Engine (AMZN_Yuyi)

We have benchmarked the RTE workflows; we have a goal for our next major release EOY to focus on: 
- Improving the onboarding experience and set up a new project (Workflow 1)
* Creating a basic breakout game as baseline (Workflow 2) 
* Creating editor extensions/new capabilities via a Gem (Workflow 8)
* Packaging and deploying a game project (Workflow 9)

Q: Where can I see the workflows and suggest new ones?

A: We will publish the workflow detail in o3de/sig-ui-ux. Bring questions and feedback to the meetings or comment on GitHub.

We're starting recruiting for RTE participation; you can sign up to run the workflows and give feedback; we will also be partnering with the O3DE game jam event to get feedback through that event as well. 

## UX Roadmap (AMZN_Yuyi)
This will be published on GitHub next month: 
- Installer
- Community Gems
- Project creation improvements
- Viewport and editor workspaces
- Asset toolbox
- Editor actions and bindings
- Prefab improvements
- Standardized Script Canvas nodes
- Documentation and design system for editor

## BlueJay Design System (AMZN_Lee)
The BlueJay Design System is the foundation of design and UI principles for anyone who is creating editor interfaces; the goal is to make it easier for developers to adapt existing research and components for O3DE interfaces rather than having to start from scratch. 

Goals longer-term could be to adapt some of these into industry best practices and standards for interactivite engines. 

Q: Is there already a link to the specs for BlueJay? 
A: We will share the link to what we have; the AWS team is cleaning up the context and removing older Lumbeyard references. 

## Open Floor 
AMZN_Joshua gave an overview of the iconography

AMZN_Yuyi introduced the topic of editor telemetry - how might we do this in a privacy-preserving manner? 


## Actions
* The UI/UX SIG leads from AWS are going to meet with other partner and community teams to understand how they operator and come upp with best practices for the O3DE UI/UX SIG. If you want to participate, let AMZN_Joshua know. 

* Next meeting is tentatively scheduled for 8/26, 11:00am Pacific / 2pm Eastern 

## Ongoing discussions

* Editor telemetry - waht are the goals? Concerns? What should we collect, and how do we keep user data safe? Best practices for the product?
    * JT suggests checking out the historic archives for Blender since this was discussed
    * There are aversions for some types of applications to any telemetry that leaves the organization (they don't want you to know the workflow in general). Maybe rather than on/off, make it highly configurable. 


