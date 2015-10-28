# Summary
---
This visualization displays the people who survived and died on the Titanic.  
The main explanatory variables for death are:  
+ gender
+ Passenger class
+ Age

# Design
---
##### Initial visualization
A bar chart is a very good way to display difference in repartition and to help compare quantity.  
Gender is the main explanatory variable of survival. It is a category measure on the x axis so that it is front and center.  
Count is a measure variables and allow to see the repartition between gender and survival.  
I think that the whole distribution and the difference between survival are well shown.
Passenger class is color coded as it is less proeminent in the survival. Passenger class reparition can be deduced but is not the main purpose of the visualization.
Finally, age is also indicative of the survival and I added it when clicking a bar: it displays the number of people who survived or perished for the selected gender and passenger class.

##### Modifications following feedbacks
The main feedbacks were related to the display of the ages. I added axis label to make it clearer. I then added both the survived and perished lines to make comparison easier.  
Finally, I added the possibility to fade one line or the other to better see a specific distribution.

# Feedbacks
---
I got feedbaks from 3 people this time. 
##### Person 1
This version is better that the first one.  
But I do not clearly understand the age distribution and what I can learn from it. The points are too packed.  
Maybe adding a 100 base bars to see proportionnal distribution as well as true values.

##### Person 2
Way clearer than the first one. I would put the axis label on the age visualizations.  

##### Person 3
I understand better now the relationships between gender, passenger class and survival. The age graphs are too complicated. It would be better to display or hide some series.  

# Resources
---
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends