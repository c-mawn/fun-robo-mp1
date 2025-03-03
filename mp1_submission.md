## Zaraius's reflection:
#### What did you learn from this? What did you not know before this assignment?
From this assignment I learnt a lot about translating theoretical math into code which controls a robot. Before this I had a very basic understanding of numpy but after a lot of time spent debugging I have a more concrete understanding of the library.
#### What was the most difficult aspect of the assignment?
The most difficult aspect of the assignment for me was debugging various aspects of the code while trying to get the simulator to run. For example our DH matrix was of the data type np.matrix instead of np.array which took hours to find. Another bug we faced was the robot was counting angles in degrees but the dh_to_matrix wanted them in radians. Without this conversion the robot would move sparatically and we tried changing many other aspects of our code until we tried this.   
#### What was the easiest or most straightforward aspect of the assignment?
The easiest aspect of the assignment was converting the simulator code into working robot code. I think it was easy because other people had already figured out a lot of the small issues with the robot so I didn't have to spend too much time on it. 
#### How long did this assignment take? What took the most time (PC setup? Coding in Python? Exploring the questions?)?
The assignment took about 15 hours to complete. Most of the time was spent on coding and debugging python code. We also spent a considerable amount of time deriving our DH matrix and the jacobian.
#### What did you learn about arm forward kinematics that we didn't explicitly cover in class?
During this assignment I learnt a geometric way to calculate the jacobian which we didn't cover in class. We learnt this approach by first asking Kene who showed it to us and then trying it on our own and then Dominic helped us solidify it.
#### What more would you like to learn about arm forward kinematics?
I would like to learn forward kinematics for differnt type of robot arms. For example I know that trying to controlling a delta arm would be different than a SCARA or a 5-dof. I would like to learn how to control parallel mechanism with multiple arms.
