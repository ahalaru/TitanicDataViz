# Titanic Data Visualization

## Summary

The sinking of the RMS Titanic in her maiden voyage is one of the most infamous shipwrecks in history. The Titanic dataset has information about 891 people, giving some basic information about them , like their Age, Sex, Class ,the fare they paid and most importantly if they survived the disaster or no. In this visualization I  represented the counts of people survived (1) and not survived (0) across age groups and further classified each Age group across Sex and Class. 

## Design

I used bar chart to show counts of survival across each age category. I used color as visual enconding to represent Pclass for each category separately for survived 0 and survived 1. And each Pclass value is divided by a line to separate counts for male and female. 

The code for the first visualization is found in index.html. After feedback-1 and feedback-2, I made the following changes to the visualization and saved it in index\_up1.html

1>Displayed the age category boundaries alongside each category name.
2>Sorted the Age category by the age values rather than alphabetically.
3>Added another visualization displaying the same data in percentage format.
4>Added title to the visualization.

The following changes were made to the *data file* after downloading

1> I Added a column called "Age\_Category" and binned them using following criteria.
"Child" for 0-12,"Young" for 13-29,"Adult" 30-59,"Senior" for 60+,"Unspecified" for records with Age not specified. 

2> I Added a column of all 1s called "Count" to aid in counting sum of people survived in individual categories.

3> After feedback-1,I changed Age\_Category values to show the age bracket they fall too. Eg: "Child" was changed to "Child 0-12" and so on. The updated data file is named as titanic\_data\_up1.tsv


## Feedbacks

I received the following feedback from friends from various sources. I made the necessary changes to the visualization as mentioned in the design section. 

### Feedback 1

What do you notice in the visualization?
Counts of people in every age group from titanic is represented in the stacked bar chart. Each bar is color coded for Pclass and further separated by a line for male and female

What questions do you have about the data?
I want to know the exact bracket in Age\_Category. What ages is classified as Adult and Young etc. 

What relationships do you notice?
The death count is largest for young and specifically the males from pclass 3. For children who did not survive, most seem to be from pclass 3 too. Survival count is largest for Adults in pcalss 1.   

What do you think is the main takeaway from this visualization?
Survival chances would be better for people in Pclass1 and and very low in pclass 3. There were fewer people in Pclass 2 compared to pclass 3 and pclass 1. 

Is there something you don’t understand in the graphic?
The visualization seems nice and self explanatory. Though it would be nice to see data in percent format too. 

### Feedback 2

The overall visualisation seems very intuitive. Though I'd recommend few changes. 

1>Change the order of the Age categories to follow natural order of smallest to oldest rather than alphabetical as it is now.
2>Explicitly specify in the visualization what survived 0 vs survived 1 means. 
3>Displaying percentages alongside the count will give greater insight into the visual.
4>Also do add a title to your visualization. Although it may seem trivial, it is the vital aspect of any data visualization.


### Feedback 3


## Resources





