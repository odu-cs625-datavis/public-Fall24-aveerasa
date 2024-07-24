# Homework 5: Analyzing Data Using Distribution Charts

**Due:** Saturday, March 30, 2024 by 11:59pm  

The goal of this assignment is gain experience creating distribution charts (histogram, eCDF, boxplot) and using them to help guide further analysis of the underlying data.

## Assignment

### Part 1: Create Distribution Charts

To start your analysis, create a **boxplot**, **histogram**, and **eCDF** for the distributions described below. 

You may use whatever tools you wish to manipulate the data and create the charts. Remember that CS students must create their charts using Python or Vega-Lite. Students from other stream should use Python or Vega lite to create one of their charts. All students may pull the datasets into a separate application and format as needed.  

All of the datasets for this assignment come from [2010 Statistical Abstract of the United States](https://www.census.gov/library/publications/2009/compendia/statab/129ed.html). 

Both the PDF tables and the Excel spreadsheets contain Notes that you should read. In particular, many of the population figures are in thousands, so you may need to do some adjustments to your data to produce accurate distributions.

**Important:** Exclude the District of Columbia (DC) from all datasets.

Pick **one** of the three datasets to work with:

1) Section 14. [Prices](https://www.census.gov/library/publications/2009/compendia/statab/129ed/prices.html). Table 713 - Single-Family Housing price Indexes by State [pg. 11 in PDF](https://www2.census.gov/library/publications/2010/compendia/statab/129ed/tables/prices.pdf)
   * boxplot: Show the Single-famiy housing price indexes of all states in 1995, 2000, and 2008
      * this should result in 3 separate boxplot glyphs in a single chart
   * eCDF and histogram: Single-famiy housing price indexes of all states in one of the years (your chart title must indicate which year)
      * your histogram should use a reasonable bin size for the data
   
2) Section 1. [Population](https://www.census.gov/library/publications/2009/compendia/statab/129ed/population.html) Table 13 - State Population--Rank, Percent Change, And Population Density [pg. 22 in PDF](https://www2.census.gov/library/publications/2010/compendia/statab/129ed/tables/pop.pdf)
   * boxplot: Show the distributions of the population density (Population per square mile of land area) in 1990, 2000, and 2008 
      * this should result in 3 separate boxplot glyphs in a single chart
   * eCDF and histogram: Show the distribution of population density in one of the years (your chart title must indicate which year)
      * your histogram should use a reasonable bin size for the data

3) Section 4. [Education](https://www.census.gov/library/publications/2009/compendia/statab/129ed/education.html) Table 228 - Educational attainment by State [pg. 41 in PDF](https://www2.census.gov/library/publications/2010/compendia/statab/129ed/tables/educ.pdf)
   * boxplot: Show the distributions of high school graduate, Bachelor's degree, and Advanced degree by state in 2007 
      * this should result in 3 separate boxplot glyphs in a single chart
   * eCDF and histogram: Show the distribution of either the High school graduate or Advanced degree in 2006 (your chart title must indicate which)
      * your histogram should use a reasonable bin size for the data

### Part 2: Further Analysis

Use the charts that you created in Part 1 to guide further investigation of the data.  I expect to see additional charts created in this part.  This could be  other types of charts that reveal something interesting.

State at least 2 interesting findings about the data and explain how you used one or more of the distribution charts to guide the investigation into this finding. These findings must be something more than a simple observation from the base charts. For example, I want something more than "80% of the states in the US have more than 1 million people". (This may or may not be true, it's just an example.)

It is fine if you want to consult additional datasets as part of your analysis.

### Things to Remember
* Look at the data before you start creating charts.
* Do a sanity-check on your results.  Do they make sense? 
* Review the in-class tutorial and read the documentation before you search the web for examples.
* Include informative axis labels and chart titles.

## Files to Include

Your GitHub repo should contain any files you used to create the charts. This includes smaller datafiles, Excel spreadsheets, Tableau workbooks, Python ipynb notebooks, Python source code, etc. Your repo should also contain images of the created charts so they can be included in your report.

## Report

Your report is an important part of this assignment.  It should be written as a narrative and not just a set of bullet points.  Your report should include your name, CS625-HW5, date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there are many spelling or grammatical errors. 

For Part 1, you must include the following items in your report:
* describe any data manipulation you needed to perform before creating the charts
* include an appropriately-sized image of the chart
* link to the chart
    * Excel, Tableau - link to your spreadsheet/workbook in your GitHub repo
    * Vega-Lite - provide a link to your notebook (see ["Note about Using Observable"](#note-about-using-observable) for sharing instructions)
    * Seaborn in Google Colab - provide a link to your notebook (make sure to share with GTA and instructor) or link to your ipynb file in your GitHub repo
    * Seaborn locally - link to your Python code in your GitHub repo
    * other tools - ask if you have questions about what should be submitted
* describe each of your charts and how they were created (explain the code you used and include code snippets)
* discuss the advantages and disadvantages of each type of chart idiom for showing these distributions (talk specifically about *these* distributions, not just their advantages and disadvantages in general)
* name 1-2 simple observations you can draw from each chart

For Part 2, you must include a full explanation of your analysis in your report, including any additional charts that were created.  How did you arrive at your findings by starting with one of the distribution charts?

As always, you must include a section titled "References", including links to any examples that you used in completing this assignment.

## Submission

You should be working in the private GitHub repo that was created for you in the odu-cs625-datavis organization. If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub.

Submit the URL of your report (not the URL of your repo) in Canvas under HW5. This should be something like

`https://github.com/odu-cs625-datavis/Spring24-asv-username/blob/main/HW4-report.md` 

*If you make changes to your report after submitting in Canvas, we will use the last commit time in your repo as your assignment submission time.*

## Note about Using Observable

Once you've been added to the @oducs-vis Observable Team, you can create private notebooks that you can use for your homework assignments. (If you have not yet been added to the team, email the GTA.)

To create a new private notebook:

* start at https://observablehq.com/@oducs-vis
* click New
* make sure **Workspace** is set to "ODUCS Vis" and **Visibility** is set to "Only You"
* click Create Notebook

To share with your instructor and GTA (for help or for grading):

* click Share
* in the **Search for a teammate** box, enter kgarg001, weiglemc (if you're in Dr. Weigle's class), or ashok-kumar-veerasamy (if you're in Dr. Veerasamy's class)
* choose "Can Edit"
* click Add
* click Save
