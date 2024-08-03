# Homework 3: Create Visualization Idioms from Real-World Data
**Due:** October 06, 2024 by 11:59pm  

## Assignment

The goal of this assignment is to give you experience creating charts from real-world data. You will be using GitHub dataset(s) to create a bar chart (any type), a scatterplot, and a multiple line chart using at least two different visualization tools.

## Data

You must choose your data from the [GitHub datasets](https://github.com/MainakRepositor/Datasets).

Here are some tips for dealing with the data:

* Select the dataset(s) that contains >=4 columns and 500 rows atleast
* Some of these dataset folders contains many .csv files. combine those and make it as single dataset.  
* You don't have to keep the data in the same format as the original spreadsheet.
* You can do whatever is needed to get the data in the proper format for your visualization tool, it doesn't have to be done via programming. However, data preprocessing must have been done before data visualization. 
* You don't have to use the same dataset for each type of idiom, as not all idioms will be appropriate for every dataset. That is, you can use 3 different dataset 
for differnt idioms
* Select and design suitable chart(s) with meaningful title and labels [Don't think too much - we are just looking for simple charts that convey sense making info to the stakeholders] 
*There are many different datasets here. We expect to see variety in the datasets that are chosen and in what is chosen to be visualized.*

## Creating the Charts

As stated above, create charts using three different idioms:

* bar/column chart (horizontal/vertial, stacked)
* scatterplot/dot plot
* multiple line/area chart

All of the charts must have a similar style ("look and feel") and must have meaningful axis labels. In addition, your charts must adhere concepts/principles/techniques explained in Chapter 5 and 7. That is, Expressiveness and Effectiveness (discreminablity, separability, pop out, separate, order & align and categorical regions :not all but the most)


After you have created the three charts, you must **recreate** one of the charts using a different tool. This recreation should look as close as possible to the original.

In summary, you will be creating **four charts**: three charts using one tool, and the fourth chart using a different tool.

## Files to Include

Your GitHub repo should contain any files you used to create the charts. This includes smaller datafiles, Excel spreadsheets, Tableau workbooks, Python ipynb notebooks, Python source code, etc. Your repo should also contain images of the created charts so they can be included in your report.

## Report

Your report is an important part of this assignment. It should be written as a narrative and not just a set of bullet points.  Your report should include your name, CS625-HW3, date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there any spelling or grammatical errors. 

Your report must contain the following sections:

**Data**

* name the table and the dataset(s) you've chosen
   
* describe any manipulation you performed on the data to prepare it for visualization, this includes choosing to use only subsets of the data (justify your decisions)

**Visualization Idioms & visual encoding choices**

* Explain how the idioms used in the charts you created were appropriate choices for your datasets
* for each chart, provide an idiom/mark/data/encode table

Below is an example for a horizontal bar chart of marriage rates per state ([markdown code](#markdown-code-for-table)). refer Chapter 7- Arrange Tables

Idiom: Bar Chart / Mark: Line
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| state name | key, categorical | vertical spatial region (y-axis) |
| marriage rate | value, quantitative | horizontal position on a common scale (x-axis) |

**Creating Charts**

* include an appropriately-sized image of each chart you created
* include a link to each chart you created
    * Excel, Tableau - link to your spreadsheet/workbook in your GitHub repo
    * Vega-Lite - provide a link to your notebook (see ["Note about Using Observable"](#note-about-using-observable) for sharing instructions)
    * Seaborn in Google Colab - provide a link to your notebook (make sure to share with GTA and instructor) or link to your ipynb file in your GitHub repo
    * Seaborn locally - link to your Python code in your GitHub repo
    * other tools - ask if you have questions about what should be submitted
* discuss any special customizations you used

**Reflection** - for the chart that you recreated in another tool, give an assesment of which tool you thought was easier to use and customize

**References** - list any resources you consulted

## Grading

We will be focusing on the following items when grading:

* was the mapping of data to idiom appropriate?
* was the idiom/mark/data/encode table correct?
* did the charts have meaningful axis labels?
* was the report complete and free of significant formatting or grammatical errors?

## Submission

You should be working in the private GitHub repo that was created for you in the odu-cs625-datavis organization. If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub.

Submit the URL of your report (not the URL of your repo) in Canvas under HW3. This should be something like

`https://github.com/odu-cs625-datavis/Fall24-asv-username/blob/main/HW3-report.md` 

*If you make changes to your report after submitting in Canvas, we will use the last commit time in your repo as your assignment submission time.*

# Appendix

## Markdown Code for Table

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
* in the **Search for a teammate** box, enter ashok-kumar-veerasamy
* choose "Can Edit"
* click Add
* click Save

Note that after the semester, you will be removed from the Team. We'll send an email to remind you and give you time to copy your notebooks elsewhere before that happens (you can transfer ownership to your own account). We would appreciate that you remove mention of CS 625 from the notebooks before making them public.
