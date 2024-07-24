# Homework 4: Arrange Tables

**Due:** Wednesday, March 9, 2024 by 11:59pm  

The goal of this assignment is to propose and implement charts based on questions asked about real-world data.  You will be demonstrating that you can choose and implement charts using appropriate idioms for the data and task, incorporating chart design principles that we have covered.

*Read through the entire assignment before starting.*

## Datasets

Choose **one** of the following datasets. Each dataset contains 8 questions that marked "#" and "##". You must answer two "##" type questions and one "#" type question of your choice using appropriate idioms via Seaborn/Vega Lite coding. Students that from Data science should answer one of their selected "##" questions in the chosen dataset by using Seaborn/Vega Lite coding and remaining selected questions can be answered by using Tableau/Excel [I prefer Tableau].  

### Dataset 1 : Citi BIke dataset (https://citibikenyc.com/system-data)
Download the file from the link: (https://raw.githubusercontent.com/odu-cs625-datavis/public-Spring24-aveerasa/master/CitiBike.csv)

**Q1:** What are the 5 least popular pick-up location(s) across the city for NY Citi Bike rental?#

**Q2:** Find the date of month(s) (January, February, and March) the bike was not used for long time?##

**Q3:** Which age group used/rented the bikes the most in winter and spring?##

**Q4:** Which age group of one-time users used the bikes least or none (did not use it all)?#

**Q5:** What were the best and worst weather conditions (temperature) considered for cycling/riding?#

**Q6:** What is the gender breakdown of active participants (Male v. Female)?#

**Q7:** On which day of the month(s) the greatest number of male customers used the bikes?##

**Q8:** What are the top 10 stations in the city for ending a journey?# 


### Dataset 2 : Air plane crashes Since 1908 (https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908)

Download the file from the link: (https://raw.githubusercontent.com/odu-cs625-datavis/public-Spring24-aveerasa/master/Airplane_Crashes_and_Fatalities_Since_1908.csv)

**Q1:** What are the 10 worst plane crashes that happened between 1908 and 2009?#

**Q2:** List the top 25 military forces by total aircraft fatalities that happened in the period between 2000 and 2009?##

**Q3:** What attributes would you select, how would you encode (stacked bar only in this context), and what is your question will be to create a meaningful stacked bar chart for this dataset?  Your answer should contain stacked bar chart with short description that explaining What, How and Why context.##

**Q4:** Select the suitable marks and channels to show all details given below:## [you may use two different marks/charts to display your answer] ##
        i.	Year with lowest number of fatalities
        ii.	Aircraft type that crashed had the highest number of people on the aircraft.


**Q5:** Does World War 2 (1939-1945) have any impact on number of fatalities? #

**Q6:** Develop a geo map that shows places where the crashes happened and number of fatalities.## 

**Q7:** Display the frequency of number of passengers boarded in crashed planes by Histogram graph.#

**Q8:** Display the frequency of number of people died in plane crash by Distribution plot.# 



### Dataset 3 : Employee compensation (https://data.world/city-of-phoenix/2b41f4f8-fe6f-48d3-8097-ad44ee5bd616)

Download the file from the link: (https://raw.githubusercontent.com/odu-cs625-datavis/public-Spring24-aveerasa/master/employee%20compnesation.csv)


**Q1:** What is the average monthly income of employee by marital status? #

**Q2:** Job satisfaction and gender:  Are women more satisfied than men at work?## 

**Q3:** What is the minimum monthly rate for age group between 40 and 60 (trend analysis)?#

**Q4:** Which department-based employees receives lowest median hourly rate? ##

**Q5:** Identify any two pairs of attributes in the dataset that have the notable positive correlation and negative correlation respectively (should be high or very high). Show your results in one bar chart with short description.  [Don’t choose the attribute pairs that gives expected results- Identify the interesting/surprising pair of attributes] ##.

**Q6:** Who work more hours- Single or Married or Divorced? [Hint: computed values to visualize] ##

**Q7:** Display the total number of employees in each education field by histogram plot. # 

**Q8:** Display the total number employees by their roles by distribution plot. #

*-------------------------------------------------------------------------------------* 


**Extra Credit [3 + 2 points]:** Select the one "##" type and one "#" question from the dataset that you have not chosen and answer those by using appropriate idioms (optional). You must use Python/Vega Lite to answer these extra credit questions (Applicable to both CS and DS students)

## Assignment

In total 3 charts (3 questions) must be prepared from the dataset you have chosen. Suppose if the question requires more than one charts then you are free to add that with clear notes stating that "why you have included one more idiom/chart" for that question(s).  

As you work through this, pay attention to detail and the visualization principles we have discussed in class when designing your charts.  Charts must have appropriately labeled axes and appropriate unit formats. In your report ([see below](#report)), you will describe the design decisions you have made, so take notes along the way as you work through your design process. 

As noted, CS students must answer their questions by using Python or Vega-Lite. DS students should answer one of their selected "##" type questions using Python or Vega Lite. 

**Special note:** All datasets were already cleaned and uploaded at GitHub and links were provided for you to download. However, Check the dataset(s) before using those.

These are all or nothing -- no partial extra credit given.  You must include a similar writeup for your extra credit charts as for the main assignment.

## Files to Include

Your GitHub repo should contain any files you used to create the charts. This includes smaller datafiles, Excel spreadsheets, Tableau workbooks, Python ipynb notebooks, Python source code, etc. Your repository should also contain images of the created charts so they can be included in your report.

## Report

Your report is an important part of this assignment. It should be written as a narrative and not just a set of bullet points.  Your report should include your name, CS625-HW4, date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there are many spelling or grammatical errors. 

Create a section for each question that you are addressing.  Each section must include the following information:

* question you're addressing
* appropriately-sized image of the chart
* link to the chart
    * Excel, Tableau - link to your spreadsheet/workbook in your GitHub repo
    * Vega-Lite - provide a link to your notebook (see ["Note about Using Observable"](#note-about-using-observable) for sharing instructions)
    * Seaborn in Google Colab - provide a link to your notebook (make sure to share with GTA and instructor) or link to your ipynb file in your GitHub repo
    * Seaborn locally - link to your Python code in your GitHub repo
    * other tools - ask if you have questions about what should be submitted
* explanation of how the idiom used in your chart is appropriate for your datasets and question (task)
* idiom/mark/data/encode table (see [markdown code](#markdown-code-for-table) for an example)
* discussion of any design decisions you made
* discussion of any special customizations you used

Your report must also contain the following sections:

* References - This is where you list any resources you consulted.

## Submission

You should be working in the private GitHub repo that was created for you in the odu-cs625-datavis organization. If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub.

Submit the URL of your report (not the URL of your repo) in Canvas under HW4. This should be something like

`https://github.com/odu-cs625-datavis/Spring24-asv-username/blob/main/HW4-report.md`

*If you make changes to your report after submitting in Canvas, we will use the last commit time in your repo as your assignment submission time.*

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
* in the **Search for a teammate** box, enter  ashok-kumar-veerasamy
* choose "Can Edit"
* click Add
* click Save
