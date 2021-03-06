# Tableau Data Story
## Summary
The visualisation is a brief walk through the tragic sinking of the Titanic more
than 100 years ago.
The key finding is that women had a survival rate of more than 70%, while less
than 20% of all men on board survived. For women travelling in the first or second
class that rate was even higher.
Also children had a higher rate of survival suggesting that "women and children
first" held true on board of Titanic.

## Links to datastories
story_v1 = https://public.tableau.com/profile/lennart.telwest#!/vizhome/TheTitanicSinkingv1/Overview?publish=yes
story_v2 = https://public.tableau.com/profile/lennart.telwest#!/vizhome/TheTitanicSinkingv2/Overview?publish=yes
story_final = https://public.tableau.com/profile/lennart.telwest#!/vizhome/TheTitanicSinking/Overview?publish=yes

## Design
### Initial Version
The first story should give an introduction to the dataset, so I chose the packed
bubbles to show the unequal distribution between men and women as well as first
and 3rd class. I chose the two bar charts to highlight the distribution of the
most influential features: gender & class. This is also the reason for them being
the two filters to the first story point.
In the second part I chose the packed bubbles, bar chart and histogram to show
the unequal distribution of embarkment and the distribution across age,
gender and city of embarkment. Also I wanted to add some consistency across the
whole story to make reading through the story easier.
In the final part I wanted to show the impact of each analysed feature to the
chances of survival by using stacked bars for gender and class to show the share
of each on the total group of survivors as well as a histogram with binned ages
to be able to visualise many data points in a readable way.

### Final Version
The main objective was to show the higher chance of survival that women on board
of the Titanic had. This is why most graphs and visualisations are split by gender.
The feedback that the visual encoding of gender was not consistent as well as not always
in place was very important to create a red line in the story.
Also the first version that included different bar charts which showed that gender
had the highest impact did not communicate it as clearly as I wished. So I decided
to go for a scatterplot that shows the impact of the class and gender on the chance
to survive.
In general the final version focused to only show a few, meaningful distribution
plots that compared the rate of survival between classes.

## Feedback
### story_v1
+ good introduction of the dataset
+ visualisation types are well picked
- visualisations in first two sections are hidden
- colour formatting is not consistent

### story_v2
- summary is missing
- dive into survival is missing
- dashboard is rather a selection of questions
-> create story around findings

## Resources
Titanic Sinking - https://en.wikipedia.org/wiki/RMS_Titanic#Sinking
Data Visualisation Playbook - https://d17h27t6h515a5.cloudfront.net/topher/2017/May/5919424e_03.datavisualizationplaybook/03.datavisualizationplaybook.pdf
Build a Pie Chart - http://onlinehelp.tableau.com/current/pro/desktop/en-us/buildexamples_pie.html
How to Show Filters in Dashboard? - https://community.tableau.com/thread/147638
Visualisation Guide - http://extremepresentation.typepad.com/blog/2006/09/choosing_a_good.html
