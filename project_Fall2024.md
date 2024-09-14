# Semester Project

**Due:** Saturday, November 30 by 11:59pm

The main goal of this project is for you to take the knowledge and background that you are learning this semester about data visualization and put it to good use in a new, creative effort.  The end product is a static *explanatory data analysis based* visualization (i.e., a single chart or group of charts presented in a single panel) that reveals something interesting.  (Three previous projects are highlighted in this [blog post](https://ws-dl.blogspot.com/2022/12/2022-12-02-visualization-class-projects.html) under the CS 625 heading, though note that they had a slightly different assignment.)

This project has two internal milestones with suggested deadlines. If you submit your milestone by the suggested deadline, then I will provide some feedback on that part of the project. I cannot guarantee to provide timely feedback on items submitted after the suggested deadlines. Also, the earlier you submit your milestone, the earlier you can receive feedback that can be applied to the next part of the project.

|milestone|main tasks|suggested deadline|
|---|---|---|
|1|choose your topic, potential datasets, brainstorm interesting questions|Sunday, Oct 13|
|2|explore data, narrow questions, sketch proposed charts|Sunday, Nov 17|
|final|final chart and report|Saturday, Nov 30|
|Demo Video|Saturday, Nov 30|
|Peer review -Demo Video|Monday, Dec 2|

The due date for semester project is: Saturday, November 30 by 11:59pm.

All listed afore notes tasks must be completed and submitted on or before due date. Late submissions will not be accepted. So, I *strongly recommend* you submit these on time. Feedback will be given for each task (milestones) after the due date. 

Detailed requirements will be found below (genral guidelines):

* This is an individual assignment. No group work allowed.
* You may use any tool of your choice to perform your data cleaning and exploratory analysis.
* If you are a Computer Science MS or PhD student, you must use either Python or Vega-Lite to build your final chart. Otherwise, you may use any tool of your choice to build your final chart. Similarly, students that from other streams (departments) expected to implement 50% of coding at least to build chart(s).
* The goal is to present your findings about your chosen topic. Although you may do exploratory analysis to understand your data, your visualization should focus on showing the audience what you learned. So, I expect to see high-quality charts produced with detail in this project.

## Milestone 1 - Topic/Datasets/Questions

In this first step of the project, you will choose a topic and dataset and brainstorm questions to explore about the data. To submit this milestone, you  will post your writeup in a Canvas Discussion Board so that you and your classmates can provide feedback on each others' work.

**Topic Selection:**  Since you can ask better questions about data you know about, you should pick a topic that you have some knowledge about or that you are personally interested in learning more about.

This is also an opportunity to use ChatGPT or other AI tool to help you brainstorm ideas and/or learn more about your topic.  As an example, I used the following prompts on the topic of climate change:

* `Help me brainstorm about visualization project topics related to climate change.`
* `Where can I find data about oceans and acidifcation?`
* `What are some climate factors that could affect ocean acidification?`

You can view the full conversation at <https://chat.openai.com/share/51344d2f-fc7c-4325-b245-8d82592cd8e0>.

**Data Sources:** Use valid data warehouses/resources (check with me). Be careful about the size of the dataset. You probably want on the order of 500s-1000s of items rather than millions.


**Questions:** Propose at least 3 questions about your topic that you could answer via visualization. For each question, state one or more hypotheses of what you might find in the data. (It doesn't matter if they turn out to be true or not.)

Good questions may involve data from multiple data sources ([examples](combining-datasets.md)) or comparisons between attributes in a large dataset, looking for correlations or patterns in the data. For example, "[How have CO2 levels and air temperature changed over time?](http://coastalslr.blogspot.com/2018/01/sea-level-rise-for-hampton-roads-2017.html)" or "What has been the main factor in winning percentage for the top 25 college football teams -- total yards offense per game, total turnovers per game, passing yards per game, or rushing yards per game?". These should be non-trivial questions that could lead to further questions, like "why is there a difference?". Make sure that the questions are ones that would be appropriate for visualization. For example, "What is the ODU football team's highest winning percentage?" is just a matter of sorting and can be answered without visualization. 

### Submission

Post the following information in the [Project Milestone 1 - Topic][https://canvas.odu.edu/courses/161812/discussion_topics/1007451] Discussion Board:

* topic (with link to ChatGPT conversation if you used it to brainstorm)
* brief statement as to why you're interested in this topic
* potential data source, with URL
* 3 potential questions with hypotheses

## Milestone 2 - Data Exploration/Sketch Charts

After choosing your topic and initial questions, you should start exploring your data. You may want to use exploratory data analysis (EDA) techniques that you have learned in this and other classes. Through this exploration, you should be narrowing down and refining your initial questions into *two questions* that can be addressed in your visualization.

Then, sketch **at least 2 or more potential charts that could address your questions**. The charts should be different idioms to allow you to evaluate which will end up being the most effective representation. These sketches should preferably be done on paper, but you may use a simple drawing tool as well. At this point, I do not want to see charts created by any tool like Excel, Tableau, or any code.

You may end up creating or coding up charts along the way as you go through the EDA process, but I want you to sketch out designs for the final charts before you spend time trying to figure out how to code them up.

### Submission

Post the following information in the [Project Milestone 2 - Sketches](https://canvas.odu.edu/courses/161812/discussion_topics/1007452) Discussion Board:

* topic
* final data source, with URL
* refined questions
* pictures of your sketches, with enough explanation so that they can be understood

## Final Chart(s)

Use principles from data journalism/storytelling/dashboard to implement and refine **your proposed charts** from Milestone 2.  You must include a headline that summarizes the main point of your charts (as opposed to a title that only describes your chart) and appropriate axis labels. You also should include annotations or context as needed.  These will be your final charts, so care should be taken in choosing fonts, colors, and other design/aesthetic aspects.

Reminder: Students in the Computer Science MS or PhD programs must use either Python or Vega-Lite to implement their final chart.Similarl, students from other departments are expected to use 50% of coding at least to design their charts (for interactive charts).

### Demo Video: By Saturday November 30 at 11.59 PM 

Create a short demo video where you walk through and explain your final visualization. You should point out the question you are addressing and how the visualization idiom you chose helps to answer the question.  Point out interesting aspects of your visualization and mention any parts that you are particularly proud of (for example, if there was something difficult that you figured out how to implement).  This demo video should be at most 5-10 minutes long and will be shared with your classmates (see [Submission](#submission) for instructions).

### Peer review: By December 2, 2024 at 11:59 PM

*In addition to submitting your own demo video (11/30/2024), by Monday, December 2 at 11:59pm, you must have provided some positive, constructive feedback or asked a question in the Discussion Board regarding at least one of your classmate's videos posted.*

### Report

As always, I expect your report to include your name, CS625, date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there are many spelling or grammatical errors.

Your report, named `project-report.md`, should include the following information:

* a brief description of your chosen datasets (including links to the original sources of the data)
* final questions that you addressed
* appropriately-sized image of your final charts
* link to your final charts (similar to [HW3](HW3-idioms.md), include whatever links or files are needed to view the implementation of your final charts)
* idiom/mark/data/encode table for the final charts (see [Markdown Code for Table](#markdown-code-for-table))
* explanation of how your final chart answers the question and how your headline fits your charts
* "Final Thoughts" section that provides a commentary on the development process, including roughly how much time you spent developing your visualization and what aspects took the most time
* "References" section that includes links to any examples and references that you used in completing this assignment

### Submission

You should be working in the private GitHub repo that was created for you in the odu-cs625-datavis organization. If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub.

Submit the URL of your report (not the URL of your repo) in Canvas under Semester Project.  *If you make changes to your report after submitting in Canvas, we will use the last commit time in your repo as your assignment submission time.*

Submit the URL of your demo video in the [Project Demo Videos](https://canvas.odu.edu/courses/161812/discussion_topics/1007455) Discussion Board.  In your reply, note if the video is publicly available (e.g., via YouTube) or if it requires an ODU login (e.g., ODU Zoom video published via Kaltura or in ODU OneDrive).

# Appendix

## Markdown Code for Table

Example idiom/mark/data/encode table

Idiom: Bar Chart / Mark: Line
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| state name | key, categorical | vertical spatial region (y-axis) |
| marriage rate | value, quantitative | horizontal position on a common scale (x-axis) |

Markdown code:  
```
Idiom: Bar Chart / Mark: Line
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| state name | key, categorical | vertical spatial region (y-axis) |
| marriage rate | value, quantitative | horizontal position on a common scale (x-axis) |
```

## Note about Using Observable

Once you've been added to the @oducs-vis Observable Team, you can create private notebooks that you can use for your homework assignments.

To create a new private notebook:

* start at https://observablehq.com/@oducs-vis
* click New
* make sure **Workspace** is set to "ODUCS Vis" and **Visibility** is set to "Only You"
* click Create Notebook

To share with your instructor and GTA (for help or for grading):

* click Share
* in the **Search for a teammate** box, enter ashok-kumar-veerasamy (if you're in Dr. Veerasamy's class)
* choose "Can Edit"
* click Add
* click Save

Note that after the semester, you will be removed from the Team. We'll send an email to remind you and give you time to copy your notebooks elsewhere before that happens (you can transfer ownership to your own account). We would appreciate that you remove mention of CS 625 from the notebooks before making them public.
