# homework_final

BL40A2010 Introduction to IoT-Based
Systems
Final Work Plan, 30.10.2021
Author: Zhou ziao

My final work plan is to design and analyze a basketball game system based on the Internet of Things, this basketball
The matching system contains many data sources, for example, it will identify real-time locations
10 players on the field (if they are not sent off) and judge whether to score.
After in-depth research, I think this idea is completely feasible. As a staunch opponent of the application
High-tech moves towards football, I think this trend is inevitable. Of course, our system is a simplified
The system needs to consider more complex issues when it is put into use.
The relationship between the basketball game system and the Internet of Things
In previous research, we know that the Internet of Things (IoT) is the interconnection of physical networks
Equipment, vehicles (also called “connected devices” and “smart devices”), buildings, and
Embedded electronics, software, sensors, actuators, and other items connected to the network
Enable these objects to collect and exchange data. The football game system is similar to
this. First of all, for the 10 players on the field, their reaction to changes on the field is
Internet of Things system. Second, the system can use sensors or other devices to sense
Keep abreast of changes on the field and formulate countermeasures. Under this system, basketball games
Will become smarter.
Some thoughts on the basketball game system
• It has some trackers that can perceive the position of players and the ball on the court in real time
• There is a magnetic field sensor on the goal, which can judge whether the basketball is complete
Enter the basket
• There will be a time subsystem to calculate overtime hours based on unexpected situations
The situation on the field, controlling the start and end of the game
• It will have an event subsystem that can sense the position of players and basketballs on the court.
Field, control substitutions, identify fouls and goals. The system is divided into three layers:
--The first layer is the first-hand data returned by various sensors, including location
Players and balls on the field, sensor status on the goal, etc.
--The second layer processes the data of the first layer and judges whether it is possible
Foul, whether there is a goal, etc.
--The third layer is the macro integration of the second layer data, such as the above score
Field, sending players and substitutions
