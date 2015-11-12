# Data-Visualization
Summary:

The data include second hand cars for sale that were published in craiglist. Each dot on the scatter plot represents the information of a single car. The Price [$] as the Y-axis, the Odometer [Km] as the X-axis, the model year as colors and the number of days since the advertisement was published as the size of each dot. The main objective of the chart is to reveal the relation between the price of the car the year and the odometer reading. The story about the data set and the explanatory chart demonstrate that: Price is positively correlated with years and negatively correlated with mileage. Clicking on early years, revealed cars with low price and high mileage and as we click on later years the dots slide up and left to represents cars with high price and low mileage. Another side story that the chart tell us is that the price is not correlated with the duration of advertisement. The interpretation of this result indicate that as long that the car price and mileage is in a reasonable range, despite the high correlation between these features there are other parameters that affect the buying.
#############################################################################################################################
Design: 

The most important features in the data set are the price and Odometers, therefore I choose to position them along the x and y axis.

The reason for choosing colors to encode the years, is that color enable us to visual grouping of similar colors. Therefore we can distinguish cars of similar years even when they are mixed between other colors.Other encodings does not allow that (for example the size of the circle will not enable us to distinguish between similar circle size). 

I use a scatter plot because that enable us to inspect single cars, this is also the reason that I included the information that pop out on mouse hover and the clickable dots that send the viewer to the advertisement page. I wanted that the viewer will be able to explore the data and perhaps find other interesting relations. 

The figure also enable us to click and choose a single year. The significance of that is for the viewer to be able to see how the correlation values change between different  years.
#############################################################################################################################
Feedback: 
My wife:

After aligning the cars along the x and y axis I was quite happy and I show that to my wife but she did not understand what the chart very much. She suggested to make it possible to see the price and year when the mouse hover on the dots. so I introduce that improvement first.
After I have done that I also added the colors that enable us to distinguish between different years. Again I asked my wife about her opinion. She thought that she would want to investigate even further in to more details. Since I could not include much more information on the chart I decided to add a clickable option that send you to another page with all the details that are available.

Mike :

First of all, in regards to your main variables, the reviewer makes a very good point about your price = 0 and mileage = 0 points: these points should probably be excluded from your dataset since your main story relies on the relationship between these variables, or other variables and these two variables. In addition, since price is a key variable that is perhaps best described as an outcome variable or dependent measure, it may make some sense to place the variable on the vertical axis. For the encoding of the year variable, I noticed that your legend for the years only shows a partial subset of years. Since there doesn't seem to be a relationship between consecutive colors (you are using a qualitative type scale), it is impossible to identify colors for years not represented in the legend, unless they are isolated from the years menu on the right side of the visualization. It is better to choose a different type of color scale that allows you to show that 1999 comes before 2000, which comes before 2001, etc. from the full plot, rather than needing to scroll through individual years. Selecting an effective color scale for the year feature may make it easier to create encodings for other features as well.

As noted by the reviewer, it is also unclear what the significance of the tooltips are. I note that the "days since published" variable is not represented in the tooltip, and it is not clear how we should be using the condition feature in our interpretations of the plot. Outside of this, some additional text on the page will be useful to provide context for what is being plotted. While the title is somewhat informative, it does not tell the full picture of what is going on. What cars are being measured, and how was the data sourced and collected? Context information like this can be useful as a caption under the visualization to help the reader get their bearings.


Reviewer :

The visualization is not using the right design encodings for its main purpose: Convey a story in a clear and simple way so viewers can pick it up quickly. The current encodings are typical of exploratory visualizations where the viewer is presented with all of the data, and the viewer can explore around and try to make conclusions about the data for himself.

Continuing with the reviewing process, I check your summary section and found: "The main objective of the chart is to reveal the relation between the price of the car the year and odometer reading.": I was able to identify the trend, although the design encodings are not appropriated, for example:

How helps to the current story to encode the information as bubbles? It would be easier for viewers to see a bar chart or similar showing the KM per Price
Why viewers need to explore through the different years? This is useful in exploratory visualizations where you include this option to allow viewers to explore the dataset, however in this case you simply want to demonstrate the relation between price and KM.
Why are you using different colors for different model years?How this helps to the main story?

Bubble sizes are related with duration of advertisements, how this helps to the main story?
As you can see most of the points I mention are related to how design considerations helps to convey the main story. Ideally your design should be oriented to force the viewer to recognize the story your visualization conveys. Your visualization is not required to be technically challenging, but to convey a story in the most clear and simple way.


Resource: 
https://google.github.io/styleguide/javascriptguide.xml#JavaScript_Style_Rules
http://d3js.org/
http://stackoverflow.com/



