# cs230software_design_document

Draw It or Lose It - Project Readme

Executive Summary:

I am Cody Adams, and this document shows the design implementation of a web based gaming application called "Draw it or Lose It".  The ultimate goal when creating this game
was to make a gaming experience that was maintainable, scalable, and efficient. We leveraged object oriented principles, and we aimed to deliver a robust, and clean codebase for 
a great gaming experience.


Design Constraints:
We had some challenges when working on this project.  Some of those challenges included scalability, maintainability, security, compatability, and performance. To address the scalability problem, we would implement efficent data management, and
distributed processing.  To solve the maintainability problem, we think that modular code will alow for quick updates, and bug fixes.  This will give us a great advantage, and give us faster development speed.  Another challenge was compatability.  When creating the app we have it in mind to be able to use the app accross platforms and different operating systems.  This will make the user experience more enjoyable.  Lasly the app experinec needs to be simple, streamlined, and overall produce an enjoyable experience fro the user. 

System Architecture View:
The architecture incorporates multipule components such as physical, and logical. Detaile descriptions are beyond the scope of this ReadME.

Domain Model:

The model consists of some key classes, and they are as follows: 
Entity class: Common methods and attributes.
Player class: players inherits from entity.
Team class: Player objects and inherits from entity.
Game Class: Team objects and inherits from entity.
Game Service Class: Game objects, ensuring a single point of entry using singleton pattern 
Singleton Tester and ProgramDriver Classes: Main methods for application execution and singleton pattern testing. 

Evaluation:
After going through many operating platforms we found that Linux was stable, and could be scalable.  Windows was good with overall support for their platform, and the tools that they have.  Mac was not very cost effective, but has great integration of Apple software.  Mobile devices, were not likely canditates for servers, but can handle server like tasks. 

Recommendations:
Our recommendation landed on AWS(Amazon Web Services) for the operating platform.  This is because it is scalable, secure, and performs at a high calibur. It supports many of the majior operating systems like Linux, Ubuntu, Amazon Linux, and Windows. 

Storage Management:
Amazon S3 was our recomendation.  Its great for storage of game assets, backups, and user data.

Memory Management:
We went with AWS.  The elastic load balancing is great for auto scaling features.

Distributed Systems and Networks:

AWS lets us use many computers that are under one system.

Security:

We get security through AWS in that we can use identity and access managment, web application firewalls, data encryption, moniotry, and threat detection. 
