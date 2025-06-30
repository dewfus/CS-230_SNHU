# CS-230_SNHU
## Client Overview & Software Requirements
The Gaming Room contracted Creative Technology Solutions (CTS) to develop a web-based version of their game **Draw It or Lose It**. The application needed to:

- Support multiple teams and players.
- Use unique names for teams and players to avoid duplication.
- Enforce a 30-second image-rendering round, with an additional 15-second opportunity for the opposing team.
- Be cross-platform compatible.
- Ensure only one instance of the game exists in memory at a time using the Singleton pattern.

## What Went Well
I effectively structured the software design document to clearly reflect client requirements and how each was addressed. Emphasis was placed on cross-platform support and reliable architecture. Additionally, the use of Java, REST APIs, and Singleton design patterns helped ensure maintainability and performance.

## Helpful Elements of the Design Process
Working through the design document helped define the system architecture and exposed potential challenges early on. It clarified how each class and relationship would be implemented and made the development process more efficient by serving as a roadmap.

## Area for Improvement
If I could revise one part of the document, I would enhance the **System Architecture View** by including a clear diagram and more detailed explanation of the tiers (presentation, logic, data). This would improve collaboration and long-term maintainability.

## User Needs & Design Interpretation
User needs were translated into functional classes with clear responsibilities using inheritance from a base `Entity` class. Requirements like name uniqueness and single-instance gameplay were fulfilled through unique ID generation and the Singleton pattern. Prioritizing user experience and clarity was critical in ensuring smooth gameplay.

## Design Approach & Future Strategy
The design was approached using modular development principles and a three-tier architecture:

- **Presentation Tier** for UI and responsiveness.
- **Logic Tier** for gameplay mechanics.
- **Data Tier** for persistence and player/team tracking.

In future projects, I plan to utilize tools like UML diagrams, use-case analysis, and responsive web frameworks to streamline the design process and ensure extensibility.

---

*This README serves as a summary reflection of the completed software design document for submission to The Gaming Room portfolio project.*
