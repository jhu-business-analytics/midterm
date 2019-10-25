# What Is the Main Cause of Poor Academic Performance in Baltimore City Public Schools?
# Explanatory Project Title
According to a report [Baltimore City is failing its children](https://www.baltimoresun.com/opinion/readers-respond/bs-ed-rr-student-test-scores-letter-20180410-story.html) from The Baltimore Sun, the Baltimore school students scored near the bottom on reading and math compared to students in other large urban areas and cities under a 2017 national assessment refered to [Baltimore students trail in key U.S. assessment](https://www.baltimoresun.com/education/bs-md-nations-report-card-20180409-story.html). In summary, only 13 percent of Batimore students reach the proficent level in eighth grade reading test while only 11 percent Baltimore students reach the proficent level in eighth grade Math test. 

Additionally, as comparison to other cities, we can find that students in Baltimore city have highest percent of low performance level ,lowest percent of high performance level, and the least change from previous year.
![alt text](https://github.com/achen120/midterm/blob/master/Baltimore_student_bad_performance1.jpg)
![alt text](https://github.com/achen120/midterm/blob/master/Baltimore_student_bad_performance2.jpg)

Our analysis in Education_and_Youth__2015__analysis.xlsx of the data [Education and Youth](https://data.baltimorecity.gov/Neighborhoods/Education-and-Youth-2015-/t7tk-reum) also support the phenomenom indicating the poor education situation in Baltimore.

Browsing through the web materials, a report [Baltimore's economy in black and white](https://money.cnn.com/2015/04/29/news/economy/baltimore-economy/) caught our attention. The poverty rate of Baltimore which is approximately 24% is amazingly high compared to 9.9% of Maryland and 11.8% of U.S in 2019. This surprisingly high Baltimore poverty rate and poor education situation lead us to think about whether there's some correlation between these two phenomenon. Such problems is very critical since we all know that Education is the best way to eradicate Poverty because those in poverty can only change their condition by learning new things. According to J. Nyerere, “Education is not a way to escape poverty,it is a way to fight it”. Meanwhile, poor education can lead to more serious result:
 - Poor health condition for lack of Physiology Knowledge
 - Financial Crisis for lack of Personal Finance management skills
 - Poor living standard for limited mind and thought
 


# Why is this a Challenge/Problem?
If the poor education situation in Baltimore is a result of high Poverty plus the poor education can actually lead to higher poverty rate, the issue falls into a vicious cycle and the situation would becomes worse in the future; it would hinder the development of Baltimore. Poverty can lead to poor academic performance, which can eventually lead to low education level. Low education level is one of the factors for unemployment. And unemployment will let people in poverty. This is a vicious cycle. We need to stop it!

<img src="https://github.com/achen120/midterm/blob/master/16.pic.jpg" width="600" height="300">

<img src="https://github.com/achen120/midterm/blob/master/8.pic.jpg" width="300" height="150">

<img src="https://github.com/achen120/midterm/blob/master/9.pic.jpg" width="400" height="200">


From the data above, we find that Low education level is one of the factors for unemployment, which will let people in poverty.


# Your Solution
For the data analysis part, we want to see how poverty related with academic Performance. By linking the High school poverty rate chart with academic performance chart published by Baltimore city schools using VLOOKUP with School name, we successfully combine all factors and poverty rate on one chart. Then, we find the correlation and coefficient between factors and poverty by regression data analysis. 

Chart below shows each variables’ relationship with poverty rate. P-value for School Performance Measure (SPM) Index is 0.017532, which is smaller than 0.05. Thus, SPM has relation with poverty rate. Since coefficient is negative, this means as poverty rate increases, academic performance become worse. 
![alt text](https://github.com/achen120/midterm/blob/master/15.pic_hd.jpg)

What's more, based on [Childfund International Organization](https://www.childfund.org/Content/NewsDetail/2147489206/), children born or raised in poverty face a number of disadvantages, most evidently in education. Poverty reduces a child’s readiness for school because it leads to poor physical health and motor skills, diminishes a child’s ability to concentrate and remember information, and reduces attentiveness, curiosity and motivation.   

One of the most severe effects of poverty in the United States is that poor children enter school with this readiness gap, and it grows as they get older. Children feel alienated from society; suffer insecurities because of their socioeconomic status; fear the consequences of their poverty; endure feelings of powerlessness; and are angry at society’s inability to aid in their struggles.

Health and Nutrition, from ['How Poverty Affects Classroom Engagement'](http://www.ascd.org/publications/educational-leadership/may13/vol70/num08/How-Poverty-Affects-Classroom-Engagement.aspx) by Eric Jensen
Overall, poor people are less likely to exercise, get proper diagnoses, receive appropriate and prompt medical attention, or be prescribed appropriate medications or interventions. A study by two prominent neuroscientists suggested that intelligence is linked to health (Gray & Thompson, 2004). The poor have more untreated ear infections and hearing loss issues (Menyuk, 1980); greater exposure to lead (Sargent et al., 1995); and a higher incidence of asthma (Gottlieb, Beiser, & O'Connor, 1995) than middle-class children. Each of these health-related factors can affect attention, reasoning, learning, and memory.
Nutrition plays a crucial role as well. Children who grow up in poor families are exposed to food with lower nutritional value. This can adversely affect them even in the womb (Antonow-Schlorke et al., 2011). Moreover, poor nutrition at breakfast affects gray matter mass in children's brains (Taki et al., 2010). Skipping breakfast is highly prevalent among urban minority youth, and it negatively affects students' academic achievement by adversely affecting cognition and raising absenteeism (Basch, 2011).

According to ['America’s Poverty-Education Link'](https://www.huffpost.com/entry/americas-poverty-education_b_1826000) by Howard Steven Friedman,The link between poverty and education can be seen at all educational levels.  From the earliest stage, pre-primary education, poorer Americans start disadvantaged. Children of parents earning less than $15,000 a year have pre-primary enrollment rates about 20 percent lower than children of parents earning more than $50,000 a year.  This pre-school disadvantage for poor people has far-reaching impacts, since students who participated in preschool education were 31 percent less likely to repeat a grade and 32 percent less likely to drop out of high school.


# Future Suggestions
Based on students’ poor academic performance in Baltimore, they might need extra help on school work. However, since most of the students are in severe poverty, paying for extra help is difficult for them. Thus, government should assign more funding on this. And school can recruit more staffs to provide teaching.

In order to come up with some more further suggestion on the issue, we tried to narrow down the idea of poverty into small pieces. Therefore, in second round analysis, we do linear regression multiple times to determined which factor caused by Poverty condition has the largest influence on the academic performance. 

From the chart below, we can clearly see that the p-value between Poverty and sense of safety is as low as 1.7E-5 which indicate an extremely high statistical significance. Meanwhile, the negative coefficient as -51.46 implies that the higher poverty rate typically in company with less sense of Safety.

![alt text](https://github.com/achen120/midterm/blob/master/16.pic_hd.jpg)

Based on the observation, we make our assumption that such sense of security has negative impact on student’s academic performance. Therefore, we do the linear regression again with sense of safety and academic performance. Chart below shows safety relationship with Academic performance. P-value for safety is 4.34E-37, which is smaller than 0.05. Thus, safety has relation with student’s Academic performance. Since coefficient is positive, this means as students have stronger sense of secure on the route to school, their academic performance rises.

![alt text](https://github.com/achen120/midterm/blob/master/Performance%20vs%20Safety.JPG)

Consequently, we tried to find out why such sense of safety affect academic performance so much.
The attentiveness and efficiency in study is one of the factors. A recent study at Sainte-Anne’s University finds that the student who felt unsafe has more symptoms of depression, making them unhappy and difficult to enjoy themselves. Such low performance in engagement and attentiveness in the classroom have long-term negative effect on students, leading to lower academic performance.
Another factor is absence from class. A report out of University of Southern California found that the unsafe feeling “reduces school attendance”. For student, staying home from class is often the easiest way to avoid danger. Such absence from the class hinder student’s performance in understanding.

We then related these factors with Baltimore current situation. A model of the most efficient routes to school for Baltimore students indicates that those who commute through areas with double the average amount of crime are 6 percent more likely to miss school.

Considering all circumstances above, we come up with the suggestion for school to provide secure bus pick-up service to guarantee the safety of students and give them a sense of security so as to raise the student’s academic performance.




