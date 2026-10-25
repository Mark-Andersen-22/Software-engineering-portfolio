# CS 230: Operating Platforms

The Gaming Room - Draw It or Lose It

Who was the client? What kind of software was to be designed? Describe briefly the client's requirements.

The client was The Gaming Room, which wanted to expand its existing Android game, Draw It or Lose It, into a web-based application. I designed the java domain model and the system architecture for an online application which was compatible with many operating systems. The game was required to support several games, teams and players while avoiding duplicate names and ids for the objects and to support timed rounds for each game, delivering images, security and the consistency of data between devices.

‘What do you think you did best in compiling this documentation?’

I had been very good at describing how the architecture recommended by the team could be used to meet the client’s requirements. I explained how the relationships between game, team, and player in terms of classes, the inheritance, encapsulation, singleton pattern, and iterator search, how memory, disk space, network, and security would affect the proposed system. I also pointed out that a singleton shares a service within one Java process but would need extra coordination across multiple servers.

What was useful to you in the course of the preparation of the design document?

The design document helped me think through the tasks that were needed before I could focus on individual methods. It clarified how a game involves a team and a player, and the shared Entity class further reduces the repetition of identity-related code. Writing down the requirements also helped me work out duplicate name checking, object lookups and identifiers. With this structure, it was easier to relate the code to the requirements and identify which features needed to be developed for web use.

If you were given the chance to revise any one part of your work on the documents, which would it be, and what changes would you make to it?

I would go into more detail about deployment and testing. The proposed architecture explains the relations between the client, the web server and the database. A diagram of the deployment would clarify the relationships, and a table of performance requirements could be added. I would also add a set of test cases that simulated the influx of multiple players, failed connections and server restarts. The additions would help the engineers judge whether the finished system meets the requirements.

How did you go about interpreting the users’ needs, and how did you translate those into your design? Why is it so important to bear in mind the users when you design?

I derived from the requirements of the customer the domain model and the proposed web architecture. The need for many players and teams guided the relationships between the classes, the need for a unique name led to the checks that created an object had to meet. The platform independence led to a browser-based interface with a server-controlled ruleset and state. The security and back-up requirements met the need to ensure a reliable game. It is important to consider the needs of the users because the technical success of a piece of code can be a perfect one, and yet not solve the problem or give a satisfying experience.

How did you approach the software design? What methods or techniques would you use to design and analyse a similar application?

In analyzing the requirements and the constraints of the client, I used the object-oriented method of the object model to organize the application, keeping in mind the cross-platform, memory, storage, network, and security constraints. In a similar project, I would like to continue the analysis, the UML diagram, and the separation of the responsibility. I would have to check the uncertain requirements sooner, build small prototypes for uncertain features, and write a test plan along with the design, and review it with the client at each phase of the implementation.
