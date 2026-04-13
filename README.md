# CS-230 Portfolio

## Portfolio Artifact
This repository contains my completed software design document for *Draw It or Lose It*, developed as part of the CS-230 Operating Platforms course. The document demonstrates my ability to analyze system requirements, design scalable software architecture, and communicate technical decisions clearly.

---

## Client Summary
The client, The Gaming Room, wanted to expand their Android-based game *Draw It or Lose It* into a web-based application that could support multiple teams and players across different platforms. The system needed to ensure unique game and team names while maintaining a consistent and organized game state across users. The goal was to create a scalable and maintainable design that could eventually support distributed environments.

---

## What I Did Well
One area I did particularly well was structuring the system using object-oriented design principles and design patterns. The use of a base `Entity` class reduced duplication across the system, while the `GameService` class implemented the singleton pattern to ensure consistent access to shared data. I also used iterator-based logic to enforce uniqueness across games, teams, and players. Overall, the design is clean, organized, and scalable.

---

## What Helped Me During Development
One of the most interesting parts of this project was working with actual code while building the design document. Instead of designing everything in isolation, I was able to look at real implementation details and understand how the system behaved in practice. This made the design process feel more grounded and helped bridge the gap between theory and implementation. It reinforced how important it is to think about structure and architecture early, especially when working with systems that will scale.

---

## What I Would Revise
If I were to revise this project, I would expand the system architecture section to include a more detailed breakdown of how components would interact in a production environment. This could include API design, service separation, and database interaction layers. While the current design is strong at the class level, adding more detail at the system level would make it even more complete.

---

## Interpreting User Needs
I interpreted the client’s needs by focusing on scalability, consistency, and usability. Ensuring that multiple users could interact with the system without conflicts was a key priority. This included enforcing unique naming and maintaining a single source of truth for game data. Considering the user’s needs is critical because it directly impacts how reliable and intuitive the system feels during use.

---

## My Design Approach
My approach to designing this software was to break the system into smaller components and assign clear responsibilities to each class. I focused on encapsulation, reuse, and separation of concerns. In the future, I would continue using object-oriented design principles along with patterns like singletons and iterators, while also placing more emphasis on distributed system planning, scalability, and performance considerations from the start.
