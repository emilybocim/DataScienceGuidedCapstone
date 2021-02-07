## Big Mountain Resort Ticket Price Report

# Emily Bocim

# February 2021

# Introduction:
	The recent addition of another chair lift increased operational costs by $1,540,000 for the season. This brought up the need to evaluate ticket prices and business operations to compensate for the additional cost and determine ways to increase revenue.

# Data:
	The initial data being used was provided by the data manager and contained market wide information on operations and features. Additional data was added to include state population and area. This was pulled from Wikipedia.

# Methodology:
	Two types of models were explored: linear regression and random forest. The random forest model was chosen for further exploration as a result of it having a lower mean absolute error and less variability during cross-validation during preprocessing and training. 

# Analysis:
	During initial model review, the top features were found to be the fast quads, the number of runs, area covered by snow making, and the vertical drop. Other features that were indicated as significant between both types of models included: the number of chair lifts, the length of the longest run, the number of trams, and the area of skiable terrain. These are features that can be further explored for options in increasing revenue.

# Results:
	Without making any further changes to business operations, the model supports increasing the ticket price from $81.00 to $94.22. The model does not take into consideration that other resorts may have lower or higher ticket prices than reasonable. However, by exploring the impact of the top features, changes can be made to business operations to further support the ticket price increase. 

Different scenarios, for Big Mountain Resort, were tested on the model and found that small changes in run length and area covered by snow making had little impact on ticket price. However, a scenario where one run was added, the vertical drop  was increased by 150 feet, and included the addition of the new chair lift, saw support for a $2 increase. 
