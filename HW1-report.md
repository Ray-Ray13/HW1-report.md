# Homework 1: Tool Setup

Torré Williams  
CS 625, Fall 2026  
Due: Sunday, September 6, 2026

## Git, GitHub

### Q1 - URL of GitHub Repo

https://github.com/Ray-Ray13/Practice-for-Class. 
This is where I uploaded two files pertaining to Chronic Disease Indicators. 
These files contains dates, types of diseases, groups, and location for ease of 
filtering.

### Q2 - Pull Command
git pull --force
Remote changes to local. it 
would make the changes remotely and 
then push the updates to your machine 
locally.

### Q3 - Local Commits
Commit changes is the option on the right hand of the screen that is green. 

We would have forgotten to commit the 
changes before pushing. 

## Markdown

### Q1 - Bulleted List

*Purple 
- Red 
+ Pink
  
The difference between bullet list amd, 
is that bullet list is without ordering, 
while numbered list is ordered.

### Q2 - Markdown Paragraph

This is a test <strong>bold 
text</strong>. <em>Awesome</em>. 
For <em><strong>class</strong></em>. 

<html>
  <head>
    <title>Class Test</title>
  </head>

Buc-ee's [These 14 cities are about to get a Buc-ee’s!](https://www.msn.com/en-us/money/economy/these-14-cities-are-about-to-get-a-buc-ee-s/ar-AA2aXFLf?uxmode=ruby&ocid=edgntpruby&pc=HCTS&cvid=6a9d7f47dc3045869f487de9a27a6749&ei=22).

### Q3 - Animal Image

![Cheetah](cheetahimage.jpeg")
 My favorite animal. Code tells us the 
 name and location path of the image.
## Tableau

### Q1 - Region Other Than the South

![Sales in the South](SalesintheSouth.png) 

![Sales in the East](SalesintheEast.png)

We were able to focus on sales from both the 
South and the East. I was able to filter around year and 
see the trends among the sales in different categories.

## Google Colab

### Q1 - URL of Google Colab Notebook

![HW1 Visualization](https://colab.research.google.com/drive/1nzaXxl-3ORH3fo916KNrQ1uSqqAPxQNB?usp=sharing)

## Python/Seaborn

### Q1 - First Penguin Image

![Q1 image](Q1image.png)
scatter plot relationship between length and depth

### Q2 - Second Penguin Image

![Q2 image](Q2image.png)
bar chart that gives a better visual between the overall body mass among three types of species

### Q3 - Outer Parenthesis
 so.Plot(penguins, x="species", y="body_mass_g")
    .add(so.Bar(), so.Agg())
we got an error message, letting us know that we are missing a key component for the code to run.

## Observable and Vega-Lite

### Q1 - markCircle to markSquare

vl.markCircle({size :200}) 
  .data(cars)
  .encode(
    vl.x().fieldQ("Miles_per_Gallon"),
    vl.y().fieldQ("Acceleration"),
    vl.tooltip().fieldN("Name"))
  .render()

### Q2 - markCircle to markPoint

Insert your answer and explanation here

### Q3 - Swap X and Y Axes on Scatterplot

vl.markCircle()
  .data(cars)
  .encode(
    vl.x().fieldQ("Miles_per_Gallon"),
    vl.y().fieldQ("Acceleration"),
    vl.tooltip().fieldN("Name"))
  .render()
  would've seen a downward trend starting from the right to the left, clusters of the categories, and potentially some outliers
### Q4 - Remove fieldN(Origin)

vl.markBar()                 
  .data(cars)
  .encode(
    vl.x().average("Miles_per_Gallon")
  )
  .render()                 
this gives us the average miles per gallon for cars
## References

Common Reasons Why `git push` Fails to Show Changes on GitHub, https://gitscripts.com/git-push-not-showing-up-on-github
Git pull https://github.com/git-guides/git-pull
