# Critter World: Simulating Evolving Artificial Life
---
**Created by: Carrie Chen, Anne Xia, Hao Huan Li, and Francis Lau for CS2112 at Cornell University**

# Project Overview 
---

This project was the culmination of three parts: 
A4: Parsing and Fault Injection
- a recursive descent parser to store programs in the critter language into an Abstract Syntax Tree
  
A5: Interpretation and Simualtion 
- an interpretor and simulator capable of executing critter programs 
  
A6: GUI and Multitrheading 
- a GUI to vizualize and interact with the critter simulations 

The final product is a simulated display of self-evolutionary artificial life forms (critters) capable of interacting with each other and the environment. We followed a variety of design patterns, such as the Vistor, the MVC, etc... to ensure separation of concerns in our work, where the world simulation becomes the model, and we implement a new view and controller for the app.  
