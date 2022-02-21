# software-architecture-of-modern-large-scale-systems
This is just my notes from this [course](https://www.udemy.com/course/software-architecture-design-of-modern-large-scale-systems/) by : [Michael Pogrebinsky](https://www.linkedin.com/in/michaelpog/)

<br>

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

<br>
<br>
<br>

### **PART 2 : The Advantages**


Software architecture can have many levels of abstraction :
- Classes / structs
- Modules / packages / libraries
- Services (processes / group of processes)

The more distributed our systems and using multiple service approach, The more our product can get the benefit of such Software Architecture like :
- Handling large amount of requests 
- Processing and storing very large amounts of data 
- Serving many users every day

Examples of such systems include :
- Ride-sharing
- Video on demand
- Social media
- Online video games
- Investment services
- Banks

If we get the architecture **RIGHT** , We can Go from a small startup to a **Multibillion-Dollar Company**

Importance of Designing and Architecture : 
- Minimize the Risks of failure system
- Not doing a good job at the design phase can :
    - Waste months of engineering time
    - Build a system that does not meet our requirements
- Restructuring a system that was not architected correctly is very hard and expensive
- So the stakes here are high

<br>
<br>
<br>

### **PART 3 : HOW to ACCOMPLISH such FEAT ?**
SDLC can be categorized like this :
Design -> Implementation -> Testing -> Deployment
![](../../../../../../var/folders/tt/75b9033d17n1v3x3pjxf9v200000gn/T/com.apple.Notes/HardLinkURLTemp/1C6C5D90-B42F-41F3-BBCA-9B8FE40424DA/1641913123/Software Development Cycle.png)

Challenges of Software Architecture :
We cannot prove Software architecture to be either : Correct or Optimal

What we can do to guarantee success is following this METHOD :
- Methodical design process
- Architectural patterns
- Best practices

<br>
<br>
<br>

### **PART 4 : Systems Design And Architectural Direct Drivers**
