# Summary
---
This visualization displays the people who survived and died on the Titanic.  
The main explanatory variables for death are:  
+ gender (pick-up list on the right as well as animation)
+ Passenger class
+ Age

# Design
---
##### Initial visualization
I wanted to display all people to show the high number of people taking part in the shipwreck. A scatterplot or bubble charts seems the best way to do that.  
Age is considered as a continuous variable here in order to space up the ticks.  
Passenger class is a categorical variable and used as such.  
Sex is a categorical variable that can be selected from an ad-hoc graph on the right side of the page. I also decided to add some animation so that the graph automatically go through the different values.

##### Modifications following feedbacks
I tried to add passenger classes as categorical variables but this ended with too much overplotting. So I modified it to a continous variable and added some jitter to it in the data preparation.  But the resulting visualization was not good: when only 1 point exists, the value should not change. So I reworked on the code for data preparation and did a numpy linspace which ended up fine.  
I switched the x and y axis to have more space between each point and avoid a little overplotting.  
I added a passenger class bar chart on the left of the main chart to serve as label and distribution visualisation.  
Regarding the sex distribution and animation, I reworked the coloring and stopped the animation first. The user can launch it if she wants or go through each value manually without having to question what is happening on her screen.  
I also reworded the variables names and completed the values for survived and embarked.

# Feedbacks
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

# Resources
---
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control
https://docs.scipy.org/doc/numpy/reference/generated/numpy.linspace.html