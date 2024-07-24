# Homework 2: Data Cleaning

**Due:** Wednesday, January 31, 2024, by 11:59 pm  

The goal of this week's assignment is to gain experience using OpenRefine for data cleaning.  

**Note:** This assignment assumes that you have already downloaded and installed [OpenRefine](https://openrefine.org) version 3.7.4 and worked through the OpenRefine tutorial from Week 2 of CS 625.

## Assignment

Write a report that describes how you carried out the tasks in Part 1 and how you arrived at the answers to the questions in Part 2.

### Report

I have not provided a template, but I expect your report to be named `HW2-report.md` in your class GitHub repo and to include your name, CS625-HW2, due date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there are many spelling/grammatical errors or your report is hard to read because of formatting issues.

As for all reports, there should be a "References" section that includes links to any examples that you used in completing this assignment.

### Part 1. Data Cleaning

Create a new project in OpenRefine and load the DSjobs.csv dataset available in <https://github.com/odu-cs625-datavis/public-Spring24-aveerasa>. If you view the raw version of the data file in GitHub, you can copy that URL directly into OpenRefine to load the data without downloading it separately.

Use OpenRefine to clean the dataset of DSjobs so that you can answer the questions in Part 2.  Look at the questions before you start cleaning so that you know what fields to pay attention to. Take notes and keep track of all operations you perform. As much as you can, use OpenRefine facets and GREL transforms to clean the data rather than manual editing (though, some cleaning will need to be done manually).
1.	Remove rows/columns:
Remove blank rows, rows that contain misleading values (-1 for example) exists in more than one column (of the same row). Remove the columns index and Competitors.

2.	Filling the values in the column(s):
Refill the misleading values exist in the column Founded as Unknown.
Similarly check values of all other columns and update the values accordingly (free to decide)

3.	Editing the values in the column:
Replace the values exist in the column *Size* by filling the highest value of it. For example, "1001 to 5000 employees" to be replaced as 5000. Blank cells of the Size column should be filled with 0. Convert the data type of this column to numeric. 

4.	Creating a new column:
Create a new column called "State name" and filled by extracting the state names exist in the column "Location". Then the column name Location must be changed as "City", and it should contain city names only.

5.	Create a new column called "Reliability" and fill its values based on the criteria given below:

|Rating          |  Reliability |
|----------------|--------------|
|between 0 to 2.0|     OK       |
|>2.0 and <=2.5  |    Good      |
|>2.5 and <=3.5  |  Very Good   |
|Above >3.5      |  Excellent   |
|----------------|--------------|

6. Create a new column called "Company age", compute and fill its age as of 2024. 


*Caution:* This is medium sized, messy dataset.  Clean the data as well as you can, with an eye towards being able to answer the questions in Part 2, but you are not expected to fully clean the entire dataset.

In your report, explain the steps you took to clean the data. Include screenshots, GREL statements, etc. as needed to clearly document what you did. If you did any manual cleaning, note that and explain why you did this manually. Include enough detail so that I am convinced that you understand how to use OpenRefine.

You will likely not have learned everything in class that you need to know to complete the assignment. I expect that you will watch the tutorials and read documentation, including documentation on the [GREL regex language](https://openrefine.org/docs/manual/grel).

When you are done cleaning the file:

* Export the file as a new CSV and save it in your repo as `HW2-DSjobs.csv`.
Extract JSON scripts containing all of the operations you performed on the file and save it in your repo as HW2-DSJobs.json. (Select Extract at the top of the Undo/Redo tab. Then copy and paste the JSON script into a new file.)

* Include links to these files in your report.

### Part 2. Analyze Cleaned Data

Use the cleaned data to answer the following questions in your report (and explain how you arrived at the answers):

1. How many jobs listed by Nonprofit organization?
1. Which state has the highest job openings?
1. List the company name(s) that has the lowest reliability level?
1. What type of job(s) advertised by companies headquartered in India?
1. Name the Biggest industry by revenue and occurrence

*I do not expect everyone to have the exact same answers. Some of these will depend upon decisions you make while cleaning the data. Note in your report any cleaning decisions you made that could impact your answers.*

## Submission

You should be working in the private GitHub repo that I created for you in the [odu-cs625-datavis organization](https://github.com/odu-cs625-datavis/).  If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub. 

For this assignment, your GitHub repository should include the following files:

* `HW2-report.md` - your report
* `HW2-DSjobs.csv` - cleaned CSV
* `HW2-DSjobs.json` - operations used to clean the data in JSON format
*  any images that you reference in your report

Submit the URL of your report (*not the URL of your repo*) in Canvas under HW2. This should be something like  
https<nolink>://github.com/odu-cs625-datavis/Spring24-asv-*username*/blob/main/HW2-report.md

*If you make changes to your report after submitting in Canvas, I will use the last commit time in your repo as your assignment submission time.*
