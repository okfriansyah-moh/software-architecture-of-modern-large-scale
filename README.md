# software-architecture-of-modern-large-scale

### **PART 1 : The Definitions**

The software architecture impacts :
- Performance and scale of the product
- Ease of adding new features
- Response to failure or security attack

If we make an insignificant architect, cost of redesign will be the big factor

What is the definition of Software Architecture ?
_The Software Architecture of a system is a high-level description of the system structure, its different components, and how those components communicate with each other to fulfill the sytems requirement and constraints._

Here is the breakdown of the definitions.
The Software Architecture of a system is a high-level description of the system structure means that :
- it is an abstraction that shows us the important components while hiding the implementation details
- Technologies or programming languages are not a part of the software architecture but a part of the implementation
- Decisions about implementation should be delayed to the very end of the design after we spike and research it deep down and find the constraints

Its different component, and how those components communicate with each other means that :
- The components here are black box elements defined by their behaviour and APIs
- The components may themselves be complex systems with their own software architecture diagrams.

to fulfill the systems requirement and constraints means that :
- Components come together to do what the system must do, which are our requirements
- The system does not do what it shouldn’t do, which are the constraints
