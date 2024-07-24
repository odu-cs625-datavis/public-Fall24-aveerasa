# CS 625, Spring 2024 Syllabus

[Jump to Summary Schedule](#summary-schedule) | 

Tues/Thurs 1.30pm-2:45pm  | [Batten Arts & Letters (BAL)](https://odu.edu/ts/labs-classrooms/technology-classrooms/bal) 2063

## Course Overview

*"The purpose of visualization is insight, not pictures." -Ben Shneiderman*

**Catalog Description:** This course covers the theory and application of data visualization. This includes issues in data cleaning to prepare data for visualization, theory behind mapping data to appropriate visual representations, introduction to visual analytics, and tools used for data analysis and visualization. Modern visualization software and tools will be used to analyze and visualize real-world datasets to reinforce the concepts covered in the course.

**Comparison to CS 725/825:** If you have already taken CS 725/825, then CS 625 is not appropriate for you. CS 625 is a prerequisite to CS 725/825.

**Differences from Previous Semesters:** There are two main changes that we are instituting this semester:

* We are replacing R with Python to be consistent with other courses in the Data Science program.
* Students in the MS in Computer Science program will be required to complete at least two assignments in Python or Vega-Lite. You may not complete the full course without doing some programming.

## Instructor Contact and Office Hours

Dr. Ashok Kumar Veerasamy

Office hours are times that I set aside each week to meet with students and answer questions. No appointment is necessary. 

My office hours will be:

* Fridays, 2:00-3:00 pm in my office: Dragas hall 1103F

If you cannot attend during regular office hours, please contact me to set up an alternate appointment time.

## Course Objectives

After completing this course, you should be able to do the following:

* Use OpenRefine to explore and clean real-world data.
* Explain the difference between exploratory (discover task) and explanatory (present task) visualizations.
* Describe the channels of visual encoding and order them from most effective to least effective.
* Identify a visualization where an inappropriate arrange design choice was made and explain why the choice was inappropriate.
* Explain how different data types map most effectively to various visualization idioms (i.e., charts).
* Explain the importance choosing an appropriate colormap.
* Given a dataset, develop questions about the data that can effectively be answered with a visualization.
* Critique and redesign an existing visualization.
* Use Tableau, Python, Vega-Lite, or other API or software to create effective standard charts, such as line charts, scatterplots, bar charts.
* Use Tableau, Python, Vega-Lite, or other API or software to create an effective visualization of real-world data.
* Explain and defend the design choices that you made in creating your visualization.

## Meeting Times and Course Delivery Method

This course will be organized based on the "flipped classroom" model. Students will be assigned readings and homework that will be due before the class meeting time. There will be few, if any, lectures by the instructor. Class time will be spent on discussions of the readings and assignments, demonstrations, and in-class work. *It is essential that each student be fully prepared to participate in class discussions each week.*

This section (CRN 17317) will be delivered face-to-face in a traditional classroom and online(live). Tues/Thurs 1.30pm-2:45am.

All course materials will be made available in Canvas (<https://canvas.odu.edu/courses/152735>) or via GitHub (<https://github.com/odu-cs625-datavis/public-Spring24-aveerasa>).

## Requirements

### Prerequisites

There are no specific course prerequisites for this course, but I expect you to be comfortable with basic statistics. Extensive programming experience is not required, but you should be familiar with basic programming concepts (variables, arrays, functions, conditionals, etc.).

Additionally, if you choose to use certain APIs (not required), you should be familiar with Unix, HTML, CSS, JavaScript, and jQuery. If you need a refresher on Unix, see the [CS 252](https://www.cs.odu.edu/~zeil/cs252/latest/Directory/outline/index.html) webpage. There are many excellent resources available online for common web languages.

### Course Materials

The required textbook for this course is [*Visualization Analysis and Design*](http://www.cs.ubc.ca/~tmm/vadbook/) by Tamara Munzner ([online version accesssible for free via ODU](https://go.oreilly.com/old-dominion-university//library/view/visualization-analysis-and/9781466508910/))

* website includes author's slides from half-day and full-day tutorials, PDF versions of all figures
  * author's full set of slides ([vadallslides-2021.pdf](https://www.cs.ubc.ca/~tmm/talks/vad/vadallslides-2021.pdf)), will be referenced in class
  * [Google Drive folder of all textbook figures](https://drive.google.com/drive/u/0/folders/1iZejJAruKBqBSqSCMqKC500Q8F4uh0gu)
* [textbook errata](http://www.cs.ubc.ca/~tmm/vadbook/errata.html)
* [author's keynote at d3.unconf](https://www.youtube.com/watch?v=jVC6SQS23ak) (55 min), overview of material from book

You will be required to write clearly about your visualization designs and design process. For writing help, I always suggest two inexpensive books:

* *Writing for Computer Science* by Justin Zobel
* *The Elements of Style* by Strunk and White

In addition, see the online student resources collected on Dr. Weigle's website: [New Student Resources page](https://weiglemc.github.io/new-student/#writing).

## Grading

### Assignment Types

Your grade in this class will be based on the following components:

**Participation** - 10%

* in addition to being present, students are expected to be prepared to talk about examples and figures in the required readings, explain learning checks, discuss their homework submissions, and participate in online discussions
* will receive points (0-2) for each week of class
* rubric:
  * 0 - no participation during the week
  * 1 - late to class or not prepared to participate
  * 2 - on time to class and actively participating in discussions and in-class work

**Learning Checks** - 10%

* preparation for the next class meeting, submitted via Canvas before the due date
* I will not correct your answers, but correct answers with references to the textbook will be provided after the due date
* rubric:
  * 0 - not submitted
  * 1 - did not answer all questions or late submission (within 48 hours of due date)
  * 2 - answered all questions and submitted on time

**Homework** - 50% [5 HWs and 1 Project work]

* implement concepts from a previous class meeting, submitted via GitHub
* grading scale: 0-10, where 10 is the absolute best (don't expect to get 10s on a regular basis)
  * 2 points are reserved for the required writeup about the assignment
  * late assignments have a maximum score of 8

**Midterm Exam** - 30%

* demonstrate comprehension and application of concepts discussed during the first half of the semester
* open book, open notes

### Grading Scale

The grading scale is as follows:

| percentage | letter |
| --- | --- |
| 100-94 | A | |
| 93-90 | A- |
| 89-88 | B+ |
| 87-84 | B |
| 83-80 | B- |
| 79-78 | C+ |
 | 77-74 | C |
| 73-70 | C- |
| 69-0 | F|

### Late Assignments

Any assignment submitted after its deadline is considered late. Submissions over 48 hours late are not accepted. This time limit includes weekends -- they are counted just like weekdays.

I reserve the right to specify that late submissions will not be accepted for particular assignments.

## Summary Schedule

*Note: This is a tentative schedule and may change during the semester. The complete schedule with assignments and due dates will be posted on Canvas.*

[ODU Spring 2024 academic schedule](https://www.odu.edu/academics/calendar/fall)

|Week |Date|Topic| Textbook Reading|
|---|---|---|---|
|1| Jan 9, 11| Introduction, What's Vis and Why Do It? | Ch 1|
|2| Jan 16, 18| Data and Data Cleaning | Ch 2|
|3| Jan 23, 25| Marks and Channels | Ch 5|
|4| Jan 30, Feb 1 |Arrange Tables | Ch 7|
|5| Feb 6, 8| Tour through the Visualization Zoo | |
|6| Tue, Feb 13<br/>Thu, Feb 15| Map Color and Other Channels<br/>Review for Mid-Term Exam | Ch 10|
|7| Tue, Feb 20<br/>Thu, Feb 22| **NO CLASS - Study Mid term exam**<br/>**MID-TERM EXAM**| |
|8| Feb 27, 29| Maps, Rules of Thumb, Chart Design| Ch 6, Ch 8.1-8.3|
|9| Mar 5, 7| Reduce Items, Exploratory Data Analysis (EDA) | Ch 13 (through 13.4.1)
|10| Mar 12, 14| Storytelling Vis |
|11| Mar 19, 21|  Multiple Views | Ch 12 (skip 12.4.4) |
|12 13| Tue, Mar 26<br/>Thu, Mar 28|Visualization Literacy, p1<br/>Visualization Literacy p2 | |
|14| Apr 9, 11| Manipulate View | Ch 11 (through 11.5)|
|15| Apr 16, 18| Project video demo presentation | Last day of classes|

## Course Policies

### Email/Canvas

Each student must check the class Canvas site and email daily. You should use our class Canvas Discussion Board to ask and answer general course-related questions. I will use Canvas Announcements to notify you about important updates (assignment deadline changes, office hours cancellations, etc.).

### Attendance

Since much of the course is based on discussion and in-class work, I expect you to arrive on time for class. Your grade will be affected if you are consistently tardy. If you have to miss a class, you are responsible checking the course Canvas site to find any assignments or notes you may have missed. Students may leave after 15 minutes if the instructor or a guest lecturer does not arrive in that time.

If there are days on which the scheduled class meeting time is cancelled due to weather or other events, there may still be assignments made and due. A post will be made to Canvas Announcements whenever the class meeting is cancelled.

### Classroom Conduct

Please be respectful of your classmates and instructor by minimizing distractions during class. Cell phones must be turned to silent during class.

### Seeking Help

The course Canvas site should be your first reference for questions about the class. If you have questions about course requirements or materials, post questions using the class Canvas Discussion Board. For extra help, attend office hours.

### Use of ChatGPT and other AI Tools

The use of ChatGPT or other AI tools is permitted *to some extent* in this class. These tools are being rapidly adopted, so it is important that you have some experience with their use. These tools are best used to help you work smarter, not do your work for you. Remember that an essential part of being in graduate school is to develop skills that you will need to be successful in the workplace. Using aids just to complete an assignment in the quest for high marks will not help you after you leave school.

I encourage you to use these tools to help you deepen your understanding and to review material you find challenging. If you use them to blindly do your homework for you, your learning will suffer and it will be obvious. But, if you use them to help clarify misunderstandings as you go, you will work and learn faster and hopefully build a solid foundation.

For all homework assignments, you must include a list of websites or other references that you consult in solving the assignment. This includes AI tools. Not only must you include the website for the tool, but you must include a link to, or screenshot of, the conversation you had with the tool. (ChatGPT has the option to create a link to a conversation.) You must also write out in your HW report the initial prompt that you used.

See [Guidelines on the Use of ChatGPT in CS 625](https://github.com/odu-cs625-datavis/public-fall23-mcw/blob/main/chat-gpt.md) for further information about using these tools in class this semester.

*Note that this does not mean that ChatGPT is acceptable for use in other courses. This policy applies only for CS 625.*

### Make-up Work

Make-ups for graded activities are possible only with a valid written medical or university excuse. It is the student's responsibility to give the instructor the written excuse and to arrange for any makeup work to be done.  A makeup exam may be different (and possibly more difficult) than the regularly scheduled exam.

### Disability Services

In compliance with PL94-142 and more recent federal legislation affirming the rights of disabled individuals, provisions will be made for students with special needs on an individual basis. The student must have been identified as special needs by the university and an appropriate letter must be provided to the course instructor. Provision will be made based upon written guidelines from the University's [Office of Educational Accessibility](https://www.odu.edu/accessibility). All students are expected to fulfill all course requirements.

Students are encouraged to self-disclose disabilities that have been verified by the Office of Educational Accessibility by providing Accommodation Letters to their instructors early in the semester in order to start receiving accommodations. Accommodations will not be made until the Accommodation Letters are provided to instructors each semester.

## Academic Integrity

Old Dominion University is committed to students' personal and academic success. In order to achieve this vision, students, faculty, and staff work together to create an environment that provides the best opportunity for academic inquiry and learning. All students must be honest and forthright in their academic studies. Your work in this course and classroom behavior must align with the expectations outlined in the Code of Student Conduct, which can be found at <https://odu.edu/oscai>.

The following behaviors along with classroom disruptions violate this policy, corrupt the educational process, and will not be tolerated.

* Cheating: Using unauthorized assistance, materials, study aids, or other information in any academic exercise.
* Plagiarism: Using someone else's language, ideas, or other original material without acknowledging its source in any academic exercise.
* Fabrication: Inventing, altering or falsifying any data, citation or information in any academic exercise.
* Facilitation: Helping another student commit, or attempt to commit, any Academic Integrity violation, or failure to report suspected Academic Integrity violations to a faculty member.

*In particular, submitting anything that is not your own work without proper attribution (giving credit to the original author) is plagiarism and is considered to be an academic integrity violation. It is not acceptable to copy source code or written work from any other source (including other students, online resources), unless explicitly allowed in the assignment statement. In cases where using resources such as the Internet is allowed, proper attribution must be given.*

Any evidence of an academic integrity violation (cheating) will result in a 0 grade for the assignment/exam, and the incident will be submitted to the Department of Computer Science for further review. Note that academic integrity violations can result in a permanent notation being placed on the student's transcript or even expulsion from the University. Evidence of cheating may include a student being unable to satisfactorily answer questions asked by the instructor about a submitted solution. Cheating includes not only receiving unauthorized assistance, but also giving unauthorized assistance. For class files kept in Unix space, students are expected to use Unix file permission protections (chmod) to keep other students from accessing the files. Failure to adequately protect files may result in a student being held responsible for giving unauthorized assistance, even if not directly aware of it.

Students may still provide legitimate assistance to one another. You are encouraged to form study groups to discuss course topics. Students should avoid discussions of solutions to ongoing assignments and should not, under any circumstances, show or share code solutions for an ongoing assignment.

All students are responsible for knowing the rules. If you are unclear about whether a certain activity is allowed or not, please contact the instructor.

More information on academic integrity is available on the ODU [academic integrity page](https://odu.edu/oscai).

## Statement from ODU Counseling Services

ODU’s [Office of Counseling Services](https://odu.edu/counselingservices) (OCS, 1526 Webb University Center) is a university agency with competent, diverse, and multidisciplinary professional staff. We are committed to supporting the emotional well-being, social development, and academic progress of all students at Old Dominion University.

College life can be a wonderful time of self-discovery, but for many, it is also a time when the awareness of mental health conditions increases. OCS services are available to assist with addressing mental health concerns that a student may be experiencing. You can learn more about the broad range of confidential mental health services available on campus via our website at <https://odu.edu/counselingservices>. All services are free to ODU students.
