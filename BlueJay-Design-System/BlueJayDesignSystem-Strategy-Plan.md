# The Blue Jay Design System Strategy

![Header-Image_2](https://user-images.githubusercontent.com/82846749/188246233-0af7aa3e-118c-4a08-b4a7-e980f3f013f0.jpg)

### **Overview**

The Blue Jay Design System (BJDS) is a unified design and development system for designers and developers who want to extend the O3DE editor. BJDS consists of a design library of reusable components for tools, and pattern guidelines that are the single source of truth for O3DE.

### **The Blue Jay design philosophy**

O3DE follows the golden rule of design systems: 

> “Systems solve the easy problems so products can solve hard problems
> more easily.” 

**– [Nathan Curtis](https://medium.com/eightshapes-llc/principles-of-designing-systems-294ee45dcf81)**

This approach allows our customers to focus on solving new and novel problems, instead of reinventing the wheel. BJDS unifies the editor to one common experience that is easy to learn and master regardless of discipline. By offering clear and consistent guidelines, it helps content creators and developers create new workflows and extend the editor for new components over time.

### **The BJDS tenets:**

* ***Efficiency*** in user interactions and workflows.
* ***Accessibility*** first options, such as color contrasts, fonts and icon legibility, interactions and scalability etc. are built into our the tool from the first step.
* ***Familiar patterns*** for visual interfaces, tools, branding, and UI elements. Don’t reinvent the wheel and confuse users.
* ***Modularity*** is key to each element of O3DE, including the interface design

### **Included in the BlueJay Design System**

The design system is divided into two parts:

1. **The Design Library:** The library that UX designers can pull down into their own design tool to help them create new workflows. This library contains pre-set styles, components and layouts to help accelerate and align the designs for the editor. These include (but aren’t limited to):
    1. **A Style Guide:** [Guidelines](https://www.o3de.org/docs/tools-ui/branding-guidelines/) around O3DE brand usage, including color, icons, and writing style.
    2. **UI Components:** The various individual components that make up the editor experience and their rules around how/when to use them in what scenario. Very important for developers building upon the QT library. For more information on this UI Checklist, see here.
    3. **UX Patterns:** Various behavioral patterns that designer and developers must consider when creating new workflows in the editor, including accessibility and industry standards.
2. **Pattern documentation:** Public documentation on [o3de.org](https://o3de.org/docs/tools-ui/) for BJDS will detail all the specs on usage, application and behaviors that have been defined for the editor so far. All the documentation will include API references, code references and visual examples, allowing developers to easily experiment with extending the editor. Documentation will cover simple text explanations and visual examples of the core components and patterns.

### **Contributions**

We welcome contributions to the Blue Jay Design System. If you want to contribute, you can find the process for contributing here: [UX Charter for UX Patterns](https://github.com/o3de/sig-ui-ux/blob/main/governance/UX%20Patterns%20for%20O3DE.md). As you consider your submissions, please remember that consistency is key to creating a holistic experience in the editor. 

If you want invent something for the system, make sure a product has a purpose for needing it; not everything belongs in the system. Refer back to our tenets when deciding whether to submit a change. 

### **Going forward**

As with all of O3DE, we will continue iterating on BJDS to ensure it’s the best system it can be. To evaluate how we’re doing, we’ll be asking ourselves:

* How long does it take users to on-board to our library?
* How clear and easy is it for users to understand our documentation?
* How many contributions are we getting from the community?

Additionally, we will use the UX/UI SIG meetings as a way to regularly check in with the community. If there is enough interest, we can host separate meetings to dive deeper into the design system.

Here is some [contact information](https://github.com/o3de/sig-ui-ux/blob/main/BlueJay-Design-System/BlueJay-Design-System-Welcome.md) if you want to talk BJDS.

## **BlueJay Design System Roadmap**

### **Future work**

Overall, out of the 89 categories, 26 pages of documentation have so far been completed with still 63 remaining. We have 3 phases of additional work planned out until end of 2023:

**Completed:**

1. **Phase 1 [Completed]**- Phase 1 covered the 26 fundamental topics that a developer/designer would need to know to extend the editor. You can find it it [here](https://o3de.org/docs/tools-ui/).

**In Progress:**

2. **Phase 2 [In Progress]** - Phase 2 focuses on publishing 16 UI Components as a Figma Design Library for the community to use. This will enable UX designers to onboard quicker and contribute to the engine - without needing to recreate all the UI components from scratch. Currently, the SIG UI UX members have been contributing time to this, and plan to have the work completed by the end of 2022. For more information on this UI Checklist, see [here](https://github.com/o3de/o3de/issues/11664).

**Future:**

3. **Phase 3 [Planned]** - Phase 3 focuses on completing the remaining 5 UI Components throughout Q1 of 2023. For more information on this UI Checklist, see [here](https://github.com/o3de/o3de/issues/11999).
4. **Phase 4 [Planned]** - Phase 4 plans to cover the 63 topics across Pattern Libraries, Components and Writing guidelines that were not covered in Phase 1. This work is planned for Q2, 2023 onwards. For information on what these 63 topics cover, will be posted soon.

If you are interested in discussing or contributing to the slated items that the SIG UI UX group is planning to focus on, you can here on our [BJDS projects board](https://github.com/orgs/o3de/projects/9/views/3).
