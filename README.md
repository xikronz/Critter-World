# Critter World: Simulating Evolving Artificial Life
**Created by: Carrie Chen, Anne Xia, Hao Huan Li, and Francis Lau for CS2112 at Cornell University**

# Project Overview 

This project was the culmination of three parts: 

[A4](https://courses.cs.cornell.edu/cs2112/2024fa/hw/a4/a4.pdf?1729789581): Parsing and Fault Injection
- a recursive descent parser to store programs in the critter language into an Abstract Syntax Tree
  
[A5](https://courses.cs.cornell.edu/cs2112/2024fa/hw/a5/a5.pdf?1731695926): Interpretation and Simualtion 
- an interpretor and simulator capable of executing critter programs 
  
[A6](https://courses.cs.cornell.edu/cs2112/2024fa/hw/a6/a6.pdf?1732396675): GUI and Multitrheading 
- a GUI to vizualize and interact with the critter simulations 

The final product is a simulated display of self-evolutionary artificial life forms (critters) capable of interacting with each other and the environment. We followed a variety of design patterns, such as the Vistor, the MVC, etc... to ensure separation of concerns in our work, where the world simulation becomes the model, and we implement a new view and controller for the app. More information on the project is available under [project specs](https://courses.cs.cornell.edu/cs2112/2024fa/project/project.pdf?1732124197)


*Note: As per Cornell University's Academic Integrity Policy, we are unable to share any of our implementations of the solution nor code to the project. This repository serves as a demonstration to some of our proudest design choices on the Graphical User Interfaces and shed some insights on the datastructures involved*

# Graphical User Interface and Simulation 
![Screenshot from 2024-12-25 21-53-03](https://github.com/user-attachments/assets/f296ab53-efda-4ca9-801b-817f4850ed1f)

Video of a simulation running at 100 steps per second 


![Screencast from 2024-12-25 09_57_22 PM (online-video-cutter com)(2)](https://github.com/user-attachments/assets/22315c2b-9f47-404b-b59e-46d3429c77c2)

# Simulation 
