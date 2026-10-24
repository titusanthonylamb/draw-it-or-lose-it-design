# Draw It or Lose It: Software Design Document

This repository contains my software design document for The Gaming Room's *Draw It or Lose It* web game.

---

## Reflection Questions

### Briefly summarize The Gaming Room client and their software requirements.

The client was The Gaming Room, an entertainment company. Their game, *Draw It or Lose It*, could only be used on Android. I was asked to design a new version which could run on other platforms such as iOS and Windows. These were the given software requirement:

- The game can have one or more teams and each team can have multiple players.
- The game and team names are to be unique. Players should be notified when a name is already in use.
- Only one game can be in memory at a time.

### What did you do particularly well in developing this documentation?

One part I did particularly well in was the design of the UML diagram. I was able to visually show how classes such as *Game*, *Team*, and *Player* inherit the base class *Entity*. Using *GameService*, I could also show how it restricted memory to only having one game in it at a time. I showed three core components of OOP (Object-Oriented Programming), being inheritance, encapsulation, and polymorphism. Lastly, *GameService* is a singleton and I was able to verify using *SingletonTester* that only one instance exists.

### What about the process of working through a design document did you find helpful when developing the code?

Working through the design document was incredibly helpful at highlighting each requirement and the steps needed to reach those requirements. The UML diagram helped me setup the classes by showing me what each class did and how it related to the others. Understanding the constraints early on led me to make changes that would have been harder to make had I learned about my constraints later on in development. 

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could pick one part of this document to redesign it would be the System Architecture View section. While not required for the project, it would still be essential in helping build the project. I would create a diagram that shows the client browsers and how they connect and correlate to the web servers. It would also show how requests are sent through HTTPS using JSON. Completing this section would support my Evaluation and Recommendations sections, specifically regarding networking, security, and storage.

### How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I took the client's needs and redesigned them into specific requirments that must be in the application. For example, to meet the need of using many platforms, I used JSON as a way to communicate to the client, which each platform can recieve and respond to. 

It is important to consider the user's needs as without directly meeting those needs, the success of the application will not be met. Redesigning so it fits the user's needs later only adds costs and adds on development time.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I started my approach to designing the software by listing the requirements and constraints for the project. I then followed by creating the UML diagram before evaluating the different platforms that could be used for the server. Lastly, I moved on to recommendations based on my evaluations. 

In the future, I would apply Agile techniques to make my requirements and constraints clear and concise. One of these techniques would be designing user stories that help highlight requirements for the project. I would also fully complete the System Architecture View section so my evaluation and recommendations could be more accurate.
