# The BlueJay Design System Strategy

### **Overview**

The BlueJay Design System (BJDS) is a unified design and development system for designers and developers who want to extend the O3DE editor. BJDS consists of a design library of reusable components for tools, and pattern guidelines that are the single source of truth for O3DE.

### **The BlueJay design philosophy**

O3DE follows the golden rule of design systems: 
**“Systems solve the easy problems so products can solve hard problems more easily.” – [Nathan Curtis.](https://medium.com/eightshapes-llc/principles-of-designing-systems-294ee45dcf81)**

This approach allows our customers to focus on solving new and novel problems, instead of reinventing the wheel. BJDS unifies the editor to one common experience that is easy to learn and master regardless of discipline. By offering clear and consistent guidelines, it helps content creators and developers create new workflows and extend the editor for new components over time.

### **BJDS tenets:**

* *Efficiency* in user interactions and workflows*.*
* *Accessibility* first*.* Accessibility options, such as color contrasts, fonts and icon legibility, interactions and scalability etc. are built into our the tool from the first step.
* *Familiar patterns* for visual interfaces, tools, branding, and UI elements. Don’t reinvent the wheel and confuse users.
* *Modularity* is key to each element of O3DE, including the interface design*.* 

### **Included in the BlueJay Design System**

The design system is divided into two parts:

1. **The Design Library:** The library that UX designers can pull down into their own design tool to help them create new workflows. This library contains pre-set styles, components and layouts to help accelerate and align the designs for the editor.  These include (but aren’t limited to):
    1. **A Style Guide:** Guidelines around O3DE brand usage, including color, icons, and writing style.
    2. **UI Components:** The various individual components that make up the editor experience and their rules around how/when to use them in what scenario. Very important for developers building upon the QT library.
    3. **UX Patterns:** Various behavioral patterns that designer and developers must consider when creating new workflows in the editor, including accessibility and industry standards.
2. **Pattern documentation:** Public documentation on [o3de.org](https://o3de.org/docs/tools-ui/) for BJDS will detail all the specs on usage, application and behaviors that have been defined for the editor so far. All the documentation will include API references, code references and visual examples, allowing developers to easily experiment with extending the editor. Documentation will cover simple text explanations and visual examples of the core components and patterns.

### **Contributions**

We welcome contributions to the BlueJay Design System. If you want to contribute, you can find the process for contributing here: [UX Charter for UX Patterns](https://github.com/o3de/sig-ui-ux/blob/main/governance/UX%20Patterns%20for%20O3DE.md). As you consider your submissions, please remember that consistency is key to creating a holistic experience in the editor. If you want invent something for the system, make sure a product has a purpose for needing it; not everything belongs in the system. Refer back to our tenets when deciding whether to submit a change. 

### **Going forward**

As with all of O3DE, we will continue iterating on BlueJay to ensure it’s the best system it can be. To evaluate how we’re doing, we’ll be asking ourselves:

* How long does it take users to on-board to our library?
* How clear and easy is it for users to understand our documentation?
* How many contributions are we getting from the community?

Additionally, we will use the UX/UI SIG meetings as a way to regularly check in with the community. If there is enough interest, we can host separate meetings to dive deeper into the design system.

## **BlueJay Design System Roadmap**

### **Future work**

Overall, out of the 89 categories, 26 pages of documentation have so far been completed with still 63 remaining. We have 4 phases of work planned:

1. **Phase 1 [Complete] -** Phase 1 covers the 26 fundamental topics that a developer/designer would need to know to extend the editor. You can find it it [here](https://o3de.org/docs/tools-ui/).
2. **Phase 2 [In Progress] -** Phase 2 focuses on documentation to help users create extensions to the editor. We expect to complete this work by the next stable O3DE release, planned for 11/30/21.
3. **Phase 3 [In Progress]** - Phase 3 covers 35 additional topics across Pattern Libraries, Components and Writing guidelines that were not covered in Phase 1. 
4. **Phase 4 [Planned]** - Phase 4 focuses on the remaining 13 items that are less critical. 

For a published roadmap on these topics in a sheet with prioritization, these will be posted on GitHub soon.

