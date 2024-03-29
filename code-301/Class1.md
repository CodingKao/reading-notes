# Class 1 Introduction to React and Components

#### Link to article: [Component-Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)
#### Link to article: [What is Props and How to Use it in React](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0)

> 

***

## Component-Based Architecture

**What is a “component”?**
> A component is a modular and reusable software object that encapsulates well-defined functionality and is designed to interact with other components through a clearly defined interface. It can be deployed independently and composed by third parties.

**What are the characteristics of a component?**
> - Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.
>
> - Replaceable − Components may be freely substituted with other similar components.
>
> - Not context specific − Components are designed to operate in different environments and contexts.
>
> - Extensible − A component can be extended from existing components to provide new behavior.
>
> - Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.
>
> - Independent − Components are designed to have minimal dependencies on other components.


**What are the advantages of using component-based architecture?**
> - Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.
>
> - Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.
>
> - Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.
>
> - Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.
>
> - Modification of technical complexity − A component modifies the complexity through the use of a component container and its services.
>
> - Reliability − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.
>
> - System maintenance and evolution − Easy to change and update the implementation without affecting the rest of the system.
>
> - Independent − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.

***

## What is Props and How to Use it in React

**What is “props” short for?**
> “Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another.

**How are props used in React?**
> Props are used to pass data from one component to another in React. Props are immutable (cannot be changed) and are used to pass data and callback functions down to child components.

**What is the flow of props?**
> Props are passed down from a parent component to a child component. The child component then uses the props to render the desired output.
