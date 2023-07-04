## DO STATES IN THE MIDWEST PERFORM BETTER ON THE SAT?

CollegeBoard, the organization that creates the SAT and AP exams, provides state reports every year that feature data about each state’s SAT performance. The reports individually are very thorough, but they make no attempt to compare the states to each other. To fill that gap, here is a map visual I’ve generated with Python to help us visualize average SAT scores by state for 2022:

![Alt Text](https://github.com/NickKrausStack/SATdata/blob/main/choro1.png)

It looks like the highest performing states form a contiguous mass in the Midwest/West - Montana, Wyoming, North Dakota, South Dakota, Nebraska, Kansas, Utah, Minnesota, Wisconsin, Missouri, Kentucky, Tennessee, and Mississippi. Only one of these states -- Mississippi -- is (somewhat) coastal. 


The difference between this Midwest/West cluster and the rest of the states is considerable. States in the cluster all have averages in the 1200s, whereas the national average, as CollegeBoard reports, is set at 1050. Does this show that students in these states smarter? That the schools are better?


Probably not. It probably has more to do with variability in participation rates. The SATs are not mandatory. This produces varying rates of participation across states. In states like New York, for instance, almost every graduating student took the SAT in 2022. But in states like North Dakota, only 1% took them.

Do participation rates affect average scores? Absolutely. In fact, we can generate another map visual to show that the high-performing states are precisely the states with very low participation rates:

![Alt Text](https://github.com/NickKrausStack/SATdata/blob/main/choro2.png)

The numbers bear this out too. The high-performing cluster states had an average participation rate of 6.6%. The total average for all the other states was 48%. 


We can also demonstrate this phenomenon in a simple line graph. As a state’s participation goes up, the average score tends to go down, albeit with a couple of outliers:

![Alt Text](https://github.com/NickKrausStack/SATdata/blob/main/choro3.png)

Why does this happen? It’s likely because a low participation rate indicates that there is a self-selection process at play. In areas where students overall do not feel obligated to take the SAT, the few that do opt in are likely to be high achievers who are perhaps more serious about college, or just have an interest in taking the test as a mental challenge. Either way, high-performing students will be overrepresented in the pool of test-takers in these areas, and that brings the average way up. But in areas where half or all students take the SAT, you don’t have this selection process. It won’t just be the high achievers taking the exam, and the average is going to be lower.


That’s not to say that all states are about equal in SAT performance when you control for participation rates. There are still real differences. For example, Oklahoma has a very low average score in spite of a very low participation rate. Georgia and Mississippi have very similar participation rates, but Mississippi’s average is 166 points greater. So there is still a discussion to be had about select states. But we can at least say with certainty that there is no contiguous cluster of states in the West that pulls way ahead of everyone else.


