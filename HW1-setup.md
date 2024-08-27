# Homework 1: Tool Setup

**Due:** September 08, 2024 by 11:59pm  

The goal of this week's assignment is to get you set up for the rest of the semester.  You'll explore Git and GitHub, Markdown, Tableau, Google Colab, Seaborn, and Observable with Vega-Lite.

There are a lot of things to explore in this assignment.  Do not attempt to do it all in one sitting.

*For this assignment only -- you may ask others in the class for help with these setup tasks.  Please use our Canvas Q&A Discussion Board for these questions so that others may benefit from the answers.*

## Reports

Each HW assignment this semester will require you to write an accompanying report. These reports must be written in Markdown (see below).  The filename for this assignment's report should be `HW1-report.md`.

For this first assignment, I am providing you with a template.  The GitHub section below will walk you through copying the template to your own repository. The questions appear in *italics*, and your answers should be in non-italic text.  Future reports do not need to include the questions.

All reports must include a heading with your name, HW number, class, and due date.  An example will be provided in the template.

### Using Outside Help

*This applies for all HW assignments.*

You may use existing code found online, and you may use tools like ChatGPT - to a certain extent. 

You may not use solutions or projects from other students, either previous or current.

For any code that you use from online sources (including ChatGPT), you must document and link to the source -- give credit where credit is due. *Use without attribution is plagiarism!* All reports must have a section labeled "References" for listing the outside resources you consulted.

### Submitting Reports

Before submitting your report, make sure to view your report file on GitHub to make sure that the formatting is done properly and all needed files have been included and all links in your report work as intended. 

## Git and GitHub

Git is a version control system for tracking changes in source code, used in the popular [GitHub](https://github.com) code hosting platform.  

The first step is to create a GitHub account. I recommend a username that incorporates at least part of your actual name. *If you already have a GitHub account, you do not need to create a new one for this class.*

Next, you need to let me know your GitHub username so that I can create a private repository (repo) for you in our class organization. This private repo will be visible only to you and me, and it's what you'll use to store your homework assignments.  Use [GitHub Issues](https://github.com/features/issues) to let me know your username:

* Open our public class repository, <https://github.com/odu-cs625-datavis/public-Fall24-aveerasa>
* Click on the **Issues** tab at the top
* Create a new issue
* The title should be your name and your GitHub username.  You should see my example in the list of Issues.
* Click **Submit New Issue**.

When I have created your private repository, you will receive an email notification via GitHub.

If you are not familiar with Git or GitHub, you should read over and walk through some of the following tutorials:

* "Hello World" at GitHub.com, <https://docs.github.com/en/get-started/quickstart/hello-world>
* Using Git source control in VS Code, <https://code.visualstudio.com/docs/sourcecontrol/overview>
* Introduction to Git in VS Code, <https://code.visualstudio.com/docs/sourcecontrol/intro-to-git>
* Introduction to GitHub in Visual Studio Code, <https://learn.microsoft.com/en-us/training/modules/introduction-to-github-visual-studio-code/>
* For a quick reference guide for git commands, see [git - the simple guide](https://rogerdudler.github.io/git-guide/)

For this class, you will only need basic Git/GitHub knowledge. To demonstrate this, perform the following tasks:

* create a new repo in your account at GitHub.com
* add two files that can contain anything you want
* clone the repo locally (on your local machine)
* Revert the files added or changes committed
* make and commit changes to one of the files in the repo locally
* push the changes back to GitHub
* open the repo in your web browser at GitHub.com
* make and commit changes to the other file in the repo on GitHub.com
* pull changes back to your local machine
* It should be noted all afore noted tuotrial operations should be executed/tested at your personal GitHub repository. The repository that we created for your class work should be used (via github commands) to submit/receive homework solution file(s) pushed from your personal github repository.

#### Items for Report

To get started on your report, copy the report template into a new file in your class repo:

* use GitHub.com to create a new file named `HW1-report.md` in your class repo (once I have created it for you)
* in a separate tab, open the report template [HW1-report.md](HW1-report.md) and click the Raw button to get the plain text version
* Select All and Copy
* paste into your HW1-report.md
* Commit changes

Edit your `HW1-report.md` and answer the following questions:

What is the URL of the new GitHub repo that you created in your personal account?

In which direction does the 'push' command work (does it send local changes to remote OR send remote changes to local)?

If you have committed a change on your local machine, but do not see the update on GitHub.com, what step might have you forgotten?

## Markdown

Markdown is a lightweight markup language that is often used in GitHub.  Here are some helpful links:

* [Markdown Basic Syntax](https://www.markdownguide.org/basic-syntax)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) (GitHub flavor)

### Inserting Images in GitHub Markdown

To include an image in your report, you'll first need to [upload the image file to your repo](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository). (When uploading files to GitHub, make sure that the filenames do not contain any spaces.) Let's assume that you have an image named `myOlympicSport.png`, and you've uploaded it to your GitHub repo in the same directory as your report Markdown file.

The syntax for displaying an image is:  
`![alt text](path_to_image)`

For the image in the same directory as your report, you can use  
`![This is a picture of my favorite sport.](myOlympicSport.png)`  
where "This is a picture of my favorite sport." will be the alt text (used for accessibility) and `myOlympicSport.png` is the filename to be displayed.

It might be the case that your image is too large to be displayed well in your report. In that case, you'll need to use HTML syntax to adjust the width or height (but not both) attributes of the image.  Here's an example:

`<img src="myOlympicSport.png" height="100" alt="This is a picture of my favorite sport.">`

#### Items for Report

Use the guides above to help you complete the following exercises in `HW1-report.md`:

Create a bulleted list with at least 3 items.

Write a single paragraph that demonstrates the use of *italics*, **bold**, ***bold italics***, `code`, and includes a link. The paragraph must explain your favorite Olympic sport/game (why you love this sport/game for example), the country that won the most olympic medals in your favorite sport in 2020 (Japan) and 2024 (France). You are free to include more information. 

Create a level 3 heading.

Find an image of an your favorite sport/game and upload it to your repo. Insert the image into your report, making sure that it is sized appropriately.

## Tableau

Sign up for [Tableau for Students](https://www.tableau.com/academic/students) to get a free one-year Tableau license.

For this assignment, go through the [Get Started with Tableau Desktop tutorial](https://help.tableau.com/current/guides/get-started-tutorial/en-us/get-started-tutorial-home.htm) through [Step 3: Focus your results](https://help.tableau.com/current/guides/get-started-tutorial/en-us/get-started-tutorial-focus.htm). In addition, watch the YouTube video to proceed further. (https://www.youtube.com/watch?v=x76lsCtCoZg). Then answer the question given in the report.md. 

#### Items for Report

Clone the file <Paris_Olympics2024.xlsx> (https://github.com/odu-cs625-datavis/public-Fall24-aveerasa/blob/main/Paris_Olympics2024.xlsx) from my repository (data taken from https://olympics.com/en/paris-2024/medals?utm_campaign=dp_google) and connect that to Tableau to design a horizontal bar chart. Your bar chart should display the countries that won most number of medals by continent. Save the chart as an image (*don't just take a screenshot*). Save the image file in your repo (*no spaces in the filename*) and include the image in your `HW1-report.md`.  

## Google Colab

[Google Colab](https://colab.research.google.com/) is a project to host Python-based Jupyter notebooks in the cloud. For more information about Google Colab, see their [FAQ](https://research.google.com/colaboratory/faq.html).

To get started, make sure you're logged into a Google account (either a personal one or your ODU student account).

Open [Overview of Colaboratory Features](https://colab.research.google.com/notebooks/basic_features_overview.ipynb). Walk through and execute the examples shown. Experiment with changing some of the code and re-execute the cells.  Below each cell you edit, create a new Text cell that indicates you made an edit.  You can describe what you changed or even just write "EDIT MADE HERE".

#### Items for Report

File > Save a copy in Drive. In the Google Drive document that opens, click on Share, then click "Change to anyone with the link", then click "Copy link" and include that link in your `HW1-report.md`.

## Python/Seaborn

If you haven't used Python much, you may want to first review the [Introduction to Python module from CS 532 Web Science](https://github.com/cci-web-science-security/web-science/blob/main/modules.md#module-2). There are lecture slides and a Google Colab notebook that walks through several examples to get you started. The page also contains a number of good Python tutorials and reference books.

Now we'll use Google Colab to walk through creating a couple different types of charts using the Seaborn library. In particular, we'll be using the new [`seaborn.objects`](https://seaborn.pydata.org/api.html#objects-api) interface.

Create a new Google Colab notebook.

Enter the following code to load the Pandas and Seaborn libraries:

```python
import pandas as pd
import seaborn.objects as so
```

Enter the following code to load in the [Palmer Penguins dataset](https://github.com/mcnakhaee/palmerpenguins) and print out the first 5 lines of the dataset:

```python
penguins = pd.read_csv("https://raw.githubusercontent.com/mcnakhaee/palmerpenguins/master/palmerpenguins/data/penguins.csv")

penguins.head()
```

Enter the following code to create a figure.

```python
(
    so.Plot(penguins, x="bill_length_mm", y="bill_depth_mm")
    .add(so.Dot())
)
```

Enter the following code to create a second figure.

```python
(
    so.Plot(penguins, x="species", y="body_mass_g", color="sex")
    .add(so.Bar(), so.Agg(), so.Dodge())
)
```

These examples come from [The seaborn.objects interface](https://seaborn.pydata.org/tutorial/objects_interface.html) tutorial.

#### Items for Report

Save each image that is created (right-click on the image and save) and insert into your report.

Describe what each figure is showing.

Remove the outer parenthesis from the code for the second figure and run the cell.  What happened? (For an explanation, see [Breaking up long lines of code in Python](https://www.pythonmorsels.com/breaking-long-lines-code-python/))

## Observable and Vega-Lite

[Observable](https://observablehq.com) is a notebook platform that is based on JavaScript. It's similar to other notebooks, but [Jupyter Notebooks](https://jupyter.org) were originally based on Python.  [Vega-Lite](http://vega.github.io/vega-lite/) is a high-level language for building interactive visualizations on the web, based on [D3](https://d3js.org).  Because it is JavaScript-based, Vega-Lite can be embedded in Observable notebooks.

Observable can be tied to your GitHub account, so to get started, make sure that you're logged into GitHub.

Read through the [A Taste of Observable](https://observablehq.com/@observablehq/a-taste-of-observable) notebook. There are no exercises to work, but this will be useful material for you going forward.

Vega Lite is a declarative language used to create, save and share interactive visualization designs. It provides a concise JSON syntax to genarate visualization in order to support analysis. Vega-Lite support interactive  multi-view graphics. (https://www.youtube.com/watch?v=3Bl5Zm422Q4)

#### Items for Report

Open the [Charting with Vega-Lite](https://observablehq.com/@observablehq/vega-lite) notebook, read through the examples, and answer the following questions in your report.

Under the scatterplot of Miles\_per\_Gallon vs. Horsepower, try replacing `markCircle()` with `markSquare()`. Then press the blue play button or use Shift-Return to run your change. What happens? How about `markPoint()`?

What change do you need to make to swap the x and y axes on the scatterplot?

The last chart in the notebook is a horizontal bar chart.  Comment out (or delete) the line `vl.y().fieldN("Origin"),`. Click on the 3 dots next to the resulting chart and choose 'Download PNG'. Insert the PNG into your report.

Why do you think this chart is the result of this code change?

## References

In the References section in your report, include links to any examples that you used in completing this assignment, including the tutorial examples that were given here. This will help you get into the habit of including such references.

## Submission

You should be working in the private GitHub repo that I created for you in the [odu-cs625-datavis organization](https://github.com/odu-cs625-datavis/) (your repo URL should look something like https<nolink>://github.com/odu-cs625-datavis/Fall24-asv-*username*/). 

If you are working locally, make sure that you have committed and pushed your local repo, including `HW1-report.md` and any images you reference, to GitHub. 

Submit the URL of your report in Canvas:

* Click on HW1 under Week 1 in Canvas.
* Under "Assignment Submission", click the "Write Submission" button.
* Copy/paste the URL of your report into the edit box
  * should be something like https<nolink>://github.com/odu-cs625-datavis/Fall24-asv-*username*/blob/main/HW1-report.md
* Make sure to "Submit" your assignment.

If you make changes to your report after submitting in Canvas, I will use the last commit time in your repo as your assignment submission time.
