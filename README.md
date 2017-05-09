The Squirclers - Data Viz Project (StrikeZone Visualization)

Project Prototype

The following packages are used:

shiny <br>
ggplot2 <br>
grid <br>
gridExtra <br>
plotly <br>
reshape


The team of Eric Lehman and Francisco Calderon are in the process of creating visualizations of the MLB strikezone.  This will be monumental work which will show that MLB umpires are biased based on the pitch count and that they also have different strikezones for left-handed and right-handed batters.  \#dataviz4life

The dataset used consists of over 500,000 MLB pitches from 2015 and 2016 for different counts, batter heights and batting stances.  The calls were either called a strike or a ball.  The location of each pitch is also included in the data set.

For the prototype, two visualizations are currently shown:

Superellipse SZ Tab:

This tab shows the results of machine learning analyses applied to the data set. A geospatial X-Y visualization is used here.  Gradient boosting models were built which created optimal superellipse representations of the strikezone for various batter stances and counts.  The Shiny tool displays the strikezone interactively depending on which counts and stances are selected.  Note that the rulebook strikezone is shown in white on the graphic. 

![Alt text](./images/superellipsetab.png?raw=true)

Likelihood Tab:

The likelihood tab shows the likelihood of a pitch being called a strike or a ball based on the current count.  A small multiples plot is created which shows the proportion of called strikes and balls for each count.  The user can interactively select the batter stance.  One can see that for 3-0 counts, strikes are more likely as you would expect.  The converse is true for an 0-2 count.

![Alt text](./images/summarytab.png?raw=true)

The authors of this prototype can be reached via email at:

Eric Lehman:  erlehman@usfca.edu <br>
Francisco Calderon:  fcalderonrodriguez@usfca.edu