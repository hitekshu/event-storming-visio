# Event Storming

## Introduction

### What is Event Storming?

Event Storming is a collaborative workshop technique used in software development and domain-driven design. It facilitates knowledge sharing among stakeholders, developers, and domain experts by allowing them to collaboratively model complex business processes. The goal is to identify key domain events (important changes in state) that occur within a system, along with the actors, commands, and aggregates involved.

Event Storming can be particularly effective for:

- Understanding complex systems.
- Identifying gaps in knowledge.
- Building a shared understanding among diverse teams.
- Driving the design of software architecture from a domain-centric perspective.

### Types of Event Storming

1. **Big Picture Event Storming**: Aimed at capturing an overview of the entire system or domain.
2. **Process Level Event Storming**: Focuses on specific business processes, diving into more detail.
3. **Design Level Event Storming**: Targets technical details to shape the architecture and design of a system.

## Installation Instructions for Event Storming Templates and Shapes in Visio

To facilitate Event Storming workshops using Microsoft Visio, you can install a custom template and shapes that are specifically designed for this purpose. Follow the steps below to install these resources:

### Prerequisites

- Microsoft Visio (2016 or later)
- Administrative privileges on your computer (if needed for installation)

### Installation Steps

1. **Download the Template and Shapes:**
   - Obtain the Event Storming Visio template (`Event Storming Template.vstx`) and the shape set (`event-storming-shapes.vssx`). These files are usually provided by your organization or can be downloaded from a shared repository.

2. **Copy the stencil to the Visio Shapes Directory:**
   - Copy the `EventStorming_Shapes.vssx` file to your Visio shapes directory. The default path is usually:
     ```
     C:\Users\<YourUsername>\Documents\My Shapes\
     ```

3. **Open the Event Storming Template in Visio:**
   - Launch Microsoft Visio.
   - Go to `File > New`.
   - Select `Templates` in the left panel.
   - Click on `New from Existing` and select the downloaded template

4. **Access the Event Storming Shapes:**
   - Once the template is open, go to the `Shapes` pane on the left side.
   - Click `More Shapes > My Shapes`.
   - Select `event-storming-shapes` to load the custom shape set.

5. **Start Modeling:**
   - You can now start using the template and shapes to model your Event Storming sessions. Drag and drop shapes onto the canvas to represent domain events, actors, commands, and aggregates.

### Tips for Effective Event Storming in Visio

- **Use Color Coding**: Utilize different colors for events, commands, and actors to enhance clarity.
- **Group Related Events**: Group events by bounded contexts or process stages to maintain structure.
- **Document as You Go**: Use the notes or text box feature to capture any discussions or decisions made during the session.

## Additional Resources

- **Event Storming Book** by Alberto Brandolini
- **Domain-Driven Design** by Eric Evans
- **Microsoft Visio Help Center**: [Visio Documentation](https://support.microsoft.com/en-us/visio)
