# d3.js_titanic-data_udacity_visuvalization

Summary:

This visualization shows the demographics of 891 of the 1317 passengers aboard the Titanic. Specifically, gender and class. There were more men than women, more third-class passengers than first class, and the most common age range was between 21 - 30. About 68% of the passengers on board perished. However, there is a large difference in the chance of survival across passenger class as well as in gender and whether one and a child. This visualization aims to emphasis the difference survival chance across categories, so that the viewers can compare it easily. This interactive chart allows the viewers to explore the category of interest.



Design:

The story in the chart is the varying chance of survival across different passenger class and between children women and men. The data I want to encode in the charts includes passenger class, gender, whether they are children, whether they survived or perished in this accident.


Chart Selections:
My main objective in this visualization is presenting what I intended to in the simplest way possible yet being informative. My choice of chart is a Bar chart due to its simplicity and Bar chart is easy to understand and good for comparison. So, a bar chart is used to show the differences across the passenger class.
Presenting multiple categories is achieved by Stacked bar chart uses color to encode the category of data. These stacked charts are also used to show the various comparisons in survivals.
Visual Encoding:
Passenger class :   X axis
Count/percentage of passengers : Y axis
Color: Survived or perished.

Library selections:
dimple.js is the primary visual library used in creating this chart. One of the advantages of dimple.js is that it is very easy to create visuals in terms of lines of code need to write. The other advantage is that it has the feature of showing data values when mouse is moved on a chart.
d3 is also used in this project. compare to dimple.js it is at lower level of abstraction. So it is not as efficient as dimple when creating charts, but it has more flexibility.
Design Changes:
I started off designing a fancy animation which illustrated all that I want to show in a loop finally stopping at a last stage for user to make sections and play with it. But when I showed this to my friend he said the animation is fancy but confusing (:O), this is the first feedback on my work. Then after some thought process I concluded that animation is confusing because it take different time to perceive the information for different people.  Animation is not included from there on to the final version.
Feedback:
Feedbacks are collected in person showing the chart,
•	Feedback 1:  The animation is confusing, removed the animation and developed the same chart. the colors that represent “survived” and “perished” are also not consistent. In some charts red represents “survived” and others it represents “perished”. It can be confusing for the viewers.
•	Feedback2: For this version of chart, there are only number of survivals on the X axis. With the feedback, I thought adding percentage would be more informative and hence added it.
•	Feedback3: This feedback mostly improved my color selection for the charts. I changed the color representing the legends, and lighter color is added to people survived to make it easier to understand. 
Resources
•	Titanic data set: https://www.kaggle.com/c/titanic-gettingStarted
•	dimple js examples: http://dimplejs.org/examples_index.html
•	RGB color chart: http://www.rapidtables.com/web/color/RGB_Color.htm















