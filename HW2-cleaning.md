# Homework 2: Data Cleaning

**Due:** September 22, 2024 by 11:59pm  

The goal of this week's assignment is to gain experience using OpenRefine for data cleaning.  

**Note:** This assignment assumes that you have already downloaded and installed [OpenRefine](https://openrefine.org) version 3.7.4 or above and worked through the OpenRefine tutorial from Week 2 of CS 625.

## Assignment

Write a report that describes how you carried out the tasks in Part 1 and how you arrived at the answers to the questions in Part 2.

### Report

I have not provided a template, but I expect your report to be named `HW2-report.md` in your class GitHub repo and to include your name, CS625-HW2, due date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there are many spelling/grammatical errors or your report is hard to read because of formatting issues.

As for all reports, there should be a "References" section that includes links to any examples that you used in completing this assignment.

### Part 1. Data Cleaning

Create a new project in OpenRefine and load the movies.csv dataset available in <https://github.com/odu-cs625-datavis/public-Fall24-aveerasa>. OR you can download it from <https://www.kaggle.com/datasets/bharatnatrayn/movies-dataset-for-feature-extracion-prediction?select=movies.csv>. If you view the raw version of the data file in GitHub, you can copy that URL directly into OpenRefine to load the data without downloading it separately.

Use OpenRefine to clean the dataset of movies so that you can answer the questions in Part 2. Look at the questions before you start cleaning so that you know what fields to pay attention to. Take notes and keep track of all operations you perform. As much as you can, use OpenRefine facets and GREL transforms to clean the data rather than manual editing (though, some cleaning needs to be done manually).
1.	Remove rows/columns:

    i.	Remove blank rows/row contain misleading values/columns that has no values (more than one column of the same row for example). Remove the column "Gross".

    ii.	Remove rows that contain misleading info. You must explain in your report the criteria you defined to remove those selected row(s)/column(s). [It should be noted movie/series may have several sequels with same name]


2.	Refilling the values in the column(s):

Refill the blank cells for the columns "Rating", "Votes", and "Run Time" to 0 and change their data type to numeric. Similarly check values of all other columns and update the values accordingly (free to decide). 

Your solution must be arrived via GREL or Python functions wherever it is required. Fill "N/A" for text type column(s) that has blank cells otherwise 0. 

Refer <https://openrefine.org/docs/manual/grelfunctions>


3.	The column "Year" has numerous ambiguous values. Follow the steps given below to proceed further.

    i.	Remove the rows if the cell value is Roman numerals/string only. 

    ii.	Replace the value of the year that enclosed by (xxxx) single year only. 
    
        Example: (2024) --> 2024, (2021-) --> 2021, 1965 TV Special --> 1965, (ii) (2012-) --> 2012 [Apply GREL/Python commands to arrive at the solution wherever is possible]

    iii. After successful execution of (i) to (iii) the "Year" column may have values in the format (xxxx-xxxx) or (<roman letter> xxxx-xxxx).  
    
    Create new columns namely "startYear" and "endYear". Then fill the their cell by extracting value(s) from "Year" column. Refer the example given below.
    
    Year --> 1966:  startYear --> 1966; endYear --> 1966
    Yea --> (1966-1969): startYear --> 1966; endYear --> 1969
    Year --> (I/II/?) (1966): startYear  1966; endYear --> 1966

    Remove the column "Year" after successful execution of steps 3.(i) - 3(iii). 


4.	Create a new column called "Verdict" and fill its values based on the criteria given below:

|   Rating       |  Verdict     |
|----------------|--------------|
| 0              |  Not known   |
|>0 and <=4.5    |    Flop      |
|>4.5 and <=6.5  |   Average    |
|>6.5 and <=8.0  |     Hit      |
| Above>8.0      |   Super Hit  |
|----------------|--------------|

*Caution:* This is medium sized, messy dataset.  Clean the data as well as you can, with an eye towards being able to answer the questions in Part 2. However, you are not expected to clean the entire dataset fully.

In your report, explain the steps you took to clean the data. Include screenshots, GREL statements, etc. as needed to clearly document what you did. If you did any manual cleaning, note that and explain why you did this manually. Include enough detail so that I am convinced that you understand how to use OpenRefine.

You will likely not have learned everything in class that you need to know to complete the assignment. I expect that you will watch the tutorials and read documentation, including documentation on the [GREL regex language](https://openrefine.org/docs/manual/grel).

When you are done cleaning the file:

* Export the file as a new CSV and save it in your repo as `HW2-Movies.csv`.
Extract JSON scripts containing all of the operations you performed on the file and save it in your repo as HW2-Movies.json. (Select Extract at the top of the Undo/Redo tab. Then copy and paste the JSON script into a new file.)

* Include links to these files in your report.

### Part 2. Analyze Cleaned Data

Use the cleaned data to answer the following questions in your report (and explain how you arrived at the answers):

1.	How many movies were listed as “Super Hit” in the year 2021?
2.	Which movie got lowest rating in the years 2018 to 2020 (excluding 0)?
3.	List the top 3 genres (no duplicates) that got highest number of votes (excluding 0)
4.	Name the director who directed the 10 minutes run time movie in the year 2020 that received lowest number of votes. The output must list name of the movie, number of votes, and genre. 
5.	List the top 5 movies that received highest number of votes, but verdict is “Flop” 


*I do not expect everyone to have the exact same answers. Some of these will depend upon decisions you make while cleaning the data. Note in your report any cleaning decisions you made that could impact your answers.*

## Submission

You should be working in the private GitHub repo that I created for you in the [odu-cs625-datavis organization](https://github.com/odu-cs625-datavis/).  If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub. 

For this assignment, your GitHub repository should include the following files:

* `HW2-report.md` - your report
* `HW2-Movies.csv` - cleaned CSV
* `HW2-Movies.json` - operations used to clean the data in JSON format
*  any images that you reference in your report

Submit the URL of your report (*not the URL of your repo*) in Canvas under HW2. This should be something like  
https<nolink>://github.com/odu-cs625-datavis/Fall24-asv-*username*/blob/main/HW2-report.md

*If you make changes to your report after submitting in Canvas, I will use the last commit time in your repo as your assignment submission time.*
Reference:
Dataset: 
https://medium.com/@FranciscoHinojosaLuna/5-datasets-to-practice-data-cleaning-27378f422e1c 

Movies : https://www.kaggle.com/datasets/bharatnatrayn/movies-dataset-for-feature-extracion-prediction?resource=download 
