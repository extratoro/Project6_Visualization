# Summary
---
This visualization displays the people who survived and died on the Titanic.  
The main explanatory variables for death are:  
+ Gender
+ Passenger class
+ Age  

The visualization especially focuses on survival by gendered and passenger class.

# Design
---
##### Initial visualization
A bar chart is a very good way to display difference in repartition and to help compare quantity.  
Gender is the main explanatory variable of survival. It is a category measure on the x axis so that it is front and center. I added a total of both sex in order to make comparison between passenger class more easy (especially with the hover giving a line).  
Count is a measure variable and allow to see the repartition between gender and survival.  It is converted to percentage here in order to facilitate comparison between survival rate in male and female.  
Passenger class is used as a grouping variable on the x axis to facilitate comparison between genders of the same class.  
I think that the whole distribution and the difference between survivals are well shown.
Survival is color coded to see repartition for a given gender/class group.  
Finally, age is also indicative of the survival and I added it when clicking a bar: it displays the number of people who survived or perished for the selected gender and passenger class.

##### Modifications following feedbacks
I did not modified anything following feedbacks as most of the points given in the previous feedbacks (8 in all) are now addressed.

# Feedbacks V3
---
I got feedbaks from 2 people this time. 
##### Person 1
Better version that addressed my point on a 100 base values.

##### Person 3
The age graph might maybe be bigger?

# Feedbacks for V2
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


# Feedbacks for V1
---
I got feedbaks from 5 people. All of them are by mail with basically no explanation of the visualisation. I wanted to see if it was speaking for itself or not.
##### Person 1
Animation is not working and the whole page is slow. It seems that clicking on the right change the value of the graphic. Also, why is the male bubble longer that the female's one? And why the hover display values in kilo?
What does a bubble represent? And the color gradient?  
I can see that the higher the class, the older the passengers. Do money comes with age?
The average age of survivors by class is less than the average age of the class. Why is that?
Men death rate is way higher than women, especially in the second class. Women tend to survive regardless of their passenger class, only the third class ones have been impacted.

The overall tendency is Women and children first. The general survival order is:  
+ Women and children from first and second class
+ Men in first class
+ Men of second
+ All the people in third

I would like to know how many people refused to be saved to save someone else.

##### Person 2
I have worked with this dataset before.
I cannot make what is the most important variable. If I remember correctly it was the Sex, why not put it in place of the passenger class?  
The age axis does not allow to see that children survive more. Maybe do some buckets?  
The color for dead/survived is strange, it would be better to have the dead in red.

##### Person 3
I think that the link between age and passenger class is striking. The color legend also helps to make sense of the dispersion.  
Zooming on a person with the hover is cool.  
What I did not understand before explanation is:  
+ the animation
+ the color on the sex: the same color is used for the main legend


##### Person 4
I did not managed to stop the animation and it made my computer slow.  
What does the letter after embarked means?  
Why is the 3 class before the 1 and 2?
As for analysis:  
All the women in first class survived and they are older than on other classes. More women perished in class 3.  
There were more men than women on the boat (normal, considering the time). Most of men in class 3 ended up dead.  
Strangely, I can see children surviving in all classes.  
There is a link between money and age: the higher the class, the richer. The average age in third class is less than in first and more concentrated around 20-30 (especially for women, between 15 and 63 in first whereas all are less than 50 in third class).
Deceased people are all around but poor and young men are more common in the deceased sub-group.  
In absolute value, there are less dead in first that in third.  
Most women survived in first and second classes. In third, men and women survival rates are not that different.  
Men in second class died a lot, except young ones.

I think the visualisation lacks a distribution of passenger in class to make some rations. 

##### Person 5
Why is it moving? It would be better to have it fixed first and click to animate.  The animation is too quick to understand what is going on.  
I can see the distribution between age and classes well, less with the sex.  
My main question is why men died more? Why children survived?  
