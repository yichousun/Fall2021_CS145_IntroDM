# CS 145: Introduction to data mining
### Instructor: Yizhou Sun
- Lecture Time: Tuesday/Thursday 10-11:50am
- classroom: WG Young CS24
- Office hours: Monday 2-3 and Tuesday 4:15-5:00 @ zoom

### TAs:
- Zongyue Qin (qinzongyue at cs.ucla.edu), office hours: Monday 9-11am @ BH 3551 (row M)
- Yewen Wang (wyw10804@gmail.com, please check Yewen's [Email Policy](https://sites.google.com/view/wyw10804/home/email-policy?authuser=0) before emailing her.), office hours: Wednesday 9-10am @ BH 3551 Conference Room, 10-11am @ zoom
- Shichang Zhang (myfirstname@cs.ucla.edu), office hours: Friday 10am-12pm @ BH 3551 Conference Room (email me if you can't find the place)


## Course Description
This course introduces basic concepts, algorithms, and techniques of data mining on different types of datasets, including (1) vector data, (2) set data, (3) sequence data, (4) text data, and (5) graph data. The class project involves hands-on practice of mining useful knowledge from large data sets. The course is an undergraduate-level computer science course. Also, the course may attract students from other disciplines who need to understand, develop, and use data mining techniques to analyze large amounts of data.

## Prerequisites
- You are expected to have background knowledge in data structures, algorithms, basic linear algebra, and basic statistics.
-	You will also need to be familiar with at least one programming language, and have programming experiences.

## Learning Objectives
- Know what data mining is and learn the basic algorithms
- Develop skills to apply data mining algorithms to solve real-world applications
- Gain initial experience in conducting research on data mining

## Grading
-	Homework: 30%
-	Midterm exam: 20%
-	Final exam: 15%
-	Course project: 25%
-	Participation: 10%

*All the deadlines are 11:59PM (midnight) of the due dates.

*Late submission policy: you will get original score * <a href="https://www.codecogs.com/eqnedit.php?latex=\mathbf{1}(t<=24)e^{-(ln(2)/12)*t}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathbf{1}(t<=24)e^{-(ln(2)/12)*t}" title="\mathbf{1}(t<=24)e^{-(ln(2)/12)*t}" /></a>, if you are t hours late.

*No copying or sharing of homework!

- You can discuss general challenges and ideas with others.
- Suspicious cases will be reported to The Office of the Dean of Students.


## Q & A
-	We will be using [Piazza](piazza.com/ucla/fall2021/cs145) for class discussion. The system is highly catered to getting you help fast and efficiently from classmates, the TAs, and myself. Rather than emailing questions to the teaching staff, I encourage you to post your questions on Piazza.
-	Sign up Piazza here: [piazza.com/ucla/fall2021/cs145](piazza.com/ucla/fall2021/cs145)
-	Tips: Answering other students' questions will increase your participation score.

## Academic Integrity Policy
"With its status as a world-class research institution, it is critical that the University uphold the highest standards of integrity both inside and outside the classroom. As a student and member of the UCLA community, you are expected to demonstrate integrity in all of your academic endeavors. Accordingly, when accusations of academic dishonesty occur, The Office of the Dean of Students is charged with investigating and adjudicating suspected violations. Academic dishonesty, includes, but is not limited to, cheating, fabrication, plagiarism, multiple submissions or facilitating academic misconduct."
For more information, please refer to the <a href="https://www.deanofstudents.ucla.edu/portals/16/documents/studentguide.pdf"> guidance </a>.

## Tentative Schedule
*Book refers to: Jiawei Han, Micheline Kamber, and Jian Pei, Data Mining: Concepts and Techniques, 3rd edition.

| Week | Date | Topic | Further Reading | Discussion Session| Homework| Course Project|
| ------- | ------ | ------ | -------- | ------ | ------ | ------ |
| Week 0 |9/23 |Introduction [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/01Intro.pdf) and Know Your Data [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/02Data_Exploration.pdf)|<ul><li>Book Chapter 1, 2, 3</li><li>[Review of probability from a course by David Blei](http://www.cs.princeton.edu/courses/archive/spring07/cos424/scribe_notes/0208.pdf) from Princeton U.</li><li>[Machine Learning Math Essentials](http://courses.washington.edu/css490/2012.Winter/lecture_slides/02_math_essentials.pdf) by Jeff Howbert from Washington U.</li><li>[http://cs229.stanford.edu/section/cs229-prob.pdf](http://cs229.stanford.edu/section/cs229-prob.pdf)</li><li>[Optimization](http://web.cs.ucla.edu/~yzsun/classes/2018Fall_CS145/Slides/optimization.pdf)|[Week0 Slides](https://docs.google.com/presentation/d/1BUCid4CmI-5IOrvywBQ2EvDVrcw8I9YZ1qZj0ltWCC8/edit?usp=sharing)</li></ul>|||
| Week 1 |9/28 |Linear Regression [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/03Vector_Data_LinearR.pdf)|[https://cs229.stanford.edu/notes2021fall/cs229-notes1.pdf](https://cs229.stanford.edu/notes2021fall/cs229-notes1.pdf)||||
| Week 1 |9/30 |Logistic Regression [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/04Vector_Data_LogisticR.pdf)|[https://cs229.stanford.edu/notes2021fall/cs229-notes1.pdf](https://cs229.stanford.edu/notes2021fall/cs229-notes1.pdf)|[Week 1 Slides](https://docs.google.com/presentation/d/1P8-sYYI4TJaGE5h9bodldNRIf2W0I5wQNSjxlneLan0/edit?usp=sharing)|HW1 Released||
| Week 2 |10/5 |Tree-based Models [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/05Decision_Tree.pdf)|<ul><li> Decision Tree: Book Chapter 8.1, 8.2</li><li>Regression Tree: [http://www.stat.cmu.edu/~cshalizi/350-2006/lecture-10.pdf](http://www.stat.cmu.edu/~cshalizi/350-2006/lecture-10.pdf)</li><li>Random Forest: [https://www.stat.berkeley.edu/~breiman/RandomForests/cc_home.htm](https://www.stat.berkeley.edu/~breiman/RandomForests/cc_home.htm)</li></ul>||||
| Week 2 |10/7 |Neural Networks [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/06NN.pdf)|<ul><li>http://neuralnetworksanddeeplearning.com/</li><li>http://www.deeplearningbook.org/</li></ul>|[Week 2 Slides](https://docs.google.com/presentation/d/12FAAfNWkOpdFq5E_x_iMHjp0j1qgMs1myUqZvnhOcG0/edit?usp=sharing)|HW1 Due (10/6 11:59pm), HW2 Released||
| Week 3 |10/12|Continue with Neural Networks|||||
| Week 3 |10/14|Practical Issues of Classification [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/07Evaluation_Classification.pdf) and K-Means [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/08ClusteringBasics.pdf) |<ul><li>Book Chapter 8.5</li><li>Book Chapter 10.1-10.4</li><ul>|[Week 3 Slides](https://docs.google.com/presentation/d/14uC4g7JQJUX3OvyhTOufFK58vWVDT-tNqdyb6KhpKzQ/edit?usp=sharing)|||
| Week 4 |10/19 |Mixture Models [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/09GMM.pdf) and Practical Issues of Clustering [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/10Evaluation_Clustering.pdf)|<ul><li>http://www.stat.cmu.edu/~cshalizi/350/lectures/29/lecture-29.pdf</li><li>http://www.cs.ubc.ca/~murphyk/Teaching/CS340-Fall06/reading/mixtureModels.pdf</li></ul>||HW2 Due (10/18 11:59pm), HW3 Released||
| Week 4 |10/21 |Text Data: Naive Bayes [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/11Text_NB.pdf) |http://www.ccs.neu.edu/home/yzsun/classes/2014Fall_CS6220/Slides/NB.pdf|[Week 4 Slides](https://docs.google.com/presentation/d/1T2FwCWcP9SOHOV5cjdtykBWZ0lVtO8sbyLyMgixrfiI/edit?usp=sharing)|||
| Week 5 |10/26 |Text Data: Topic Models [[Slides]](http://web.cs.ucla.edu/~yzsun/classes/2021Fall_CS145/Slides/12Text_TopicModel.pdf) |<ul><li>pLSA tutorial: http://arxiv.org/pdf/1212.3900.pdf</li><li>David Blei's ICML 2012 Tutorial: http://www.cs.columbia.edu/~blei/talks/Blei_ICML_2012.pdf</li></ul>||HW3 Due (10/25 11:59pm)||
| Week 5 |10/28 |Time Series Data  |||||
| Week 6 |11/2 |Set Data: Frequent Pattern Mining and Association Rules I |||||
| Week 6 |11/4 |Midterm Exam |||| 11/7 Midterm Report Due|
| Week 7 |11/9 |Set Data: Frequent Pattern Mining and Association Rules II ||||| 
| Week 7 |11/11 |**Veterans Day holiday (No Class)** |||||
| Week 8 |11/16 |Sequence Data: Sequential Pattern Mining |||||
| Week 8 |11/18 |Sequence Data: Dynamic Time Warping (DTW)  |||||
| Week 9 |11/23 |Graph Data: Random Walk |||||
| Week 9 |11/25 |**Thanksgiving holiday (No Class)** |||||
| Week 10 |11/30 |Graph Data: Classification and Clustering |||||
| Week 10 |12/2 | TBD||||12/5 Kaggle Submission Stop|
| Week 11 |12/9 |Final Exam||||12/10 Final Report Due|
