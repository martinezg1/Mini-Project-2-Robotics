# Mini-Project-2-Robotics

# Introduction
Robotic operating system (ROS) is an open source platform that contains a wide variety of tools, libraries, and functionality to help develop robots. It is not a traditional operating system, such as Windows or MacOS. Rather, the unique aspect of ROS is the ability to share work with other developer. What this means is that the developers of robots help build upon the foundation of ROS to give it additional functions by adding their own tools and libraries for other to use. After many years, ROS has grown into a platform to help simplify the robotic development process. This facilitates development by eliminating the need to build from the ground up. 

# Summary of References
1.	http://wiki.ros.org/ROS/Introduction
An official wiki page for ROS. Has many useful tutorials and information of how ROS works. 

2.	M. a. G. B. a. S. W. D. Quigley, Programming Robots with ROS: A Practical Introduction to the Robot Operating System, O'Reilly Media, Inc., 2015.
A textbook about develop robots with ROS.

3.	https://www.youtube.com/watch?v=9U6GDonGFHw
A YouTube tutorial on a introduction to ROS and a tutorial on how to get started with using a simulation program and packages.

# Analysis of Results
- Emphasis in sharing and collaboration between developers
- Developers can create their own software and upload it for others to use
- How ROS operates (High-level analysis):

	Nodes - processes that perform computations. An example can be a range finder or a motor. 
	
	Master – List nodes and allows nodes to communicate with each other.
	
	Messages – the data being sent from nodes to another node.
	
	Topic- each message has a topic. A node can publish and subscribe a topic. Once a node publishes a topic, any node that 	is subscribed to that topic will receive the data.  
	
	Services- similar to topic but can send requests and receive replies to another node. Difference is a node can request a 	specific node instead of publishing a topic for all nodes that are subscribed to receive.
	
	Bags- Store data collected by nodes	
	
Image of how ROS operates :
	
![alt text](https://www.generationrobots.com/img/cms/articles%20et%20tutoriels/ROS/Concepts-de-base-de-ROS.jpg)
	
(https://www.generationrobots.com/img/cms/articles%20et%20tutoriels/ROS/Concepts-de-base-de-ROS.jpg)	

Pros and Cons:

Pros:
-	Many programing languages are used such as Python, C++, MySQL, but depends on how the software was written.
-	Designed to be light. Code can be integrated in other robotic software framework.
-	An active community that are still posting software.
-	A strong software selection accumulated over the past years.
-	Great for prototyping and research.

Cons:
-	Limited operating system availability. ROS tested only in Linux and MacOS. Possible for Windows OS, but not official. Linux is the official way.
-	Software you need may not be available 
- Issues with latancy when dealing with real time data.


# Recommendations
For a person beginning to use ROS for the first time, make sure you have Linux-based operating system is needed to run ROS, such as Ubuntu. Since there is a lot of components to learn about in ROS. The official ROS.org website has tutorials to help beginners get started. Tutorials include how configure your workspace since ROS involves using the Unix terminal. Also, programming experience is needed. ROS is uses many different programming languages, but knowing how to program in Python or C++ is a good foundation for learning ROS.

# Conclusions
ROS is a powerful tool for robotic development. ROS is open source and fosters a collaborative community. Developers that are specialized in a certain aspect of robotics can upload their packages for others to use. Also, ROS is compatible with many programing languages. This gives people the flexibility to program with a language that fits with their project. ROS is especially useful for prototyping and researching purposes.

# Summary of Group Members Reports

Gu Haoqi's Report:
--------------------------------------------------------------------------------------------------------------------------------
Description of Report: 
Focused on an analysis of the paper “ROS-based Autonomous Navigation Wheelchair using Omnidirectional Sensor.” The paper was able to use the ROS framework to develop a wheelchair that can be controlled autonomously. This was accomplished by using a PCB board to control the wheelchair, a omnidirectional camera to collect imagaes, and infared and ultrasound platform to collect data regarding its surrounding area. Also, it uses algorithms to choose the best path for the wheelchair and avoid any obstacles. 

New things learned:
I learned that for development of autonomous robots using ROS, the algorithms to control the robot is the most crucial part. Putting more effort into creating and testing the algorithm can help with development. Also, a good simulation program to test the algorithm and design of the robot for efficient implementation.

Johnathan Anischenko 's Report:
--------------------------------------------------------------------------------------------------------------------------------
Description of Report: 
An overview of the the main components of ROS. This includes core components, such as communication infrastructure and robot specific features. Also included are methods of integration of the ROS framework. 

New things learned:
There are a variety of open source projects that can be use to implement ROS. 



Margot Bauman's Report:
--------------------------------------------------------------------------------------------------------------------------------
Description of Report: 
Assessed the posibility to implement ROS for self-driving wheelchair. Starts with the question of how can the wheelchair operate by itself. With this question, ROS was analyzed to see if it can fulfill the requirements needed. Positives about ROS is that it is adaptable and flexble. Some cons is ROS is more for research purposes rather than commercial usage. Issues with this is that it can have security flaws. Also, the structure of how ROS operate can be an issue due to the the way ROS communicates with the nodes. Services and topics are inefficient and can produce a bottleneck. ROS may be able to use for development, but other method can be more efficient.

New things learned: 
ROS is vulnerable to security issues. Also, the communication method of ROS can introduce bottlenecks and reduce efficiency. ROS was not designed for real time data processing.

