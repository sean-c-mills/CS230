# CS230
Module 8 Journal

1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

   The client for the project was The Gaming Room, a company that developed an Android game called Draw It or Lose It. Their goal was to expand the game so that it could run as
   a web-based application accessible on multiple platforms, including Windows, macOS, Linux, and mobile browsers. They wanted a scalable and maintainable software design that
   preserved their original game functionality while making it compatible across the many different operating systems and devices. This means creating a solution that handled
   multiple users at once, maintained consistent performance, and delivering a familiar but also upgraded user interface for a wider group of users.

2. What did you do particularly well in developing this documentation?

   One section that I believe I did well on was the Design Constraints section during the Project Software Design document. I clearly outlined the key technical limitations and
   considerations, such as the need to handle concurrent users, maintain unique identifiers for players and teams, and make sure there was scalability and platform compatibility.
   I also tied these constraints to specific design patterns like the Singleton and Iterator patterns to show how they directly solve real design challenges. This section helped
   connect practical concerns with theoretical solutions, which to me is a strong point of the document.
   
3. What about the process of working through a design document did you find helpful when developing the code?

   Working through the design document helped me think critically about the overall structure and flow of the software before I began writing any of the code. It encouraged me to break
   down the problem into different parts like architecture and system constraints. This planning phase made it easier for me to visualize how different components would interact with each
   other, and it helped me from making common mistakes. It also helped make sure the code would be scalable and maintainable by encouraging thoughtful design from the beginning rather than
   having to deal with problems later on.

4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

   If I could revise one part of my design document, I would expand on the Requirements section. While the section currently lists the main business and technical needs, I think it could provide more
   detail to give the developers and stakeholders a stronger roadmap. For example, I could separate the requirements into functional and nonfunctional requirements, which is something I learned in my
   CS255 class. Functional requirements would explain what the system must do in more detail, such as handling concurrent user logins, supporting different browsers, or saving player progress. Nonfunctional
   requirements would describe qualities like performance expectations, reliability standards, and security needs. I would also add acceptance criteria so it would be clear how each requirement could be
   tested and confirmed. 
   
5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

   To interpret the user’s needs, I started by analyzing the current Android version of the game and identifying its core functionality. Then I considered what features would need to change or expand to
   support the game on the web and cross-platform. For example, users expect fast response times and a smooth interface regardless of the device being used, so performance and UI consistency became key
   priorities. It’s important to consider the user’s needs in software design because users determine whether the software is successful or not. If the product is confusing, slow, or inconsistent, it will
   lead to frustration and lower usage.
   
6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

   I approached the design by first understanding the client’s goals, then identifying the functional and nonfunctional requirements. I used object-oriented principles and patterns to plan out how the
   components like games, players, and teams would interact. For future projects, I would continue using UML diagrams and design patterns to guide development. I would also use feedback from stakeholders
   earlier in the process to validate the design before implementation. Keeping the user experience and scalability in mind from the beginning is a strategy that I plan to use going forward.
    
