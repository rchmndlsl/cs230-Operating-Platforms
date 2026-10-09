
# The Gaming Room | Software Design & Operating Platforms

## Project Overview

This project focuses on designing a scalable, cross-platform solution for The Gaming Room, a client seeking to expand its existing Android game, *Draw It or Lose It*, into a web-based application.

The software design process involved analyzing client requirements, comparing operating platforms, and recommending an architecture that supports performance, security, and future growth.

## Skills Demonstrated

- Software architecture and system design
- Windows, Linux, and macOS platform analysis
- Object-oriented design and the Singleton pattern
- Scalability and distributed systems
- Security and memory management considerations
- Client requirements analysis
- Technical documentation

## Project Deliverable

**Software Design Document:** An evaluation of operating environments, application architecture, and technical recommendations for The Gaming Room.

---
  
# cs230-Operating-Platforms
Software Design Document for The Gaming Room - CS-230 Final Project

Briefly summarize The Gaming Room client and their software requirements.

The client, The Gaming Room, wanted to expand their game, Draw It or Lose It, from an Android-only application into a web-based game that could support multiple operating systems and users. The software needed to allow multiple teams and players to participate simultaneously while ensuring that game names remained unique, only one game instance existed at a time, and the application could scale efficiently as the number of users increased. The design also needed to consider security, memory management, storage, networking, and compatibility across platforms.

What did you do particularly well in developing this documentation?

One of my strengths was thoroughly analyzing each operating platform before making a recommendation. Rather than simply selecting a platform, I compared Windows, Linux, macOS, and mobile environments while considering scalability, performance, security, and cost. I also clearly explained how object-oriented design patterns, memory management, and distributed systems would support the client's long-term goals.

What about the process of working through a design document did you find helpful when developing the code?

Creating the design document before writing code helped organize the project into manageable pieces. It encouraged me to think through the application's architecture, user requirements, and technical constraints before implementation. By planning classes, relationships, and system requirements ahead of time, it became much easier to understand how the software should function and how different components would interact.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I were to revise one section, I would expand the system architecture diagrams and include additional UML diagrams to better illustrate the relationships between classes and the flow of data throughout the application. Adding more visual representations would make the documentation easier for both developers and stakeholders to understand while improving communication during development.

How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I focused on translating the client's business requirements into technical solutions. For example, I incorporated the Singleton design pattern to ensure only one game instance could exist, used unique identifiers to prevent duplicate names, and recommended a scalable cloud-based Linux environment to support multiple simultaneous users. Considering the user's needs is essential because software is ultimately created to solve their problems. Designing around those needs results in a product that is more reliable, efficient, easier to maintain, and more likely to meet the client's expectations.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached software design by first identifying the client's functional and technical requirements before evaluating possible solutions. I compared different operating platforms, considered design patterns, analyzed performance and security requirements, and documented recommendations before implementation. In future projects, I would continue using UML diagrams, object-oriented design principles, design patterns, and incremental planning to ensure the software architecture is scalable, maintainable, and aligned with user requirements. I also recognize the value of documenting decisions early, as it helps reduce development issues later in the project.
