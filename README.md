# Data-Visualization
Summary:
The data include second hand cars for sale that were published in craiglist. Each dot on the scatter plot represents the information of a single car. The Price [$] as the X-axis, the Odometer [Km] as the Y-axis, the model year as colors and the number of days since the advertisement was published as the size of each dot. The main objective of the chart is to reveal the relation between the price of the car the year and odometer reading. The interesting story about the data set and the explanatory chart demonstrate that very nicely as a short story: Price is positively correlated with years and negatively correlated with mileage. Clicking on early years, revealed low price cars with high mileage and as we click on later years the dots slide down right to represents high price cars with low mileage. Another side story that the chart tell us is the no corelation between the duration of advertisment with the other features. The interpetation of this result indicate that as long that the car price and milage is in the reasnable range, that will not be what make people to buy the car. 

Design: 
The most important features in the data set are the price and Odometers, therefore I choose to position them along the x and y axis. 

The color encode the years, the reason for that is that we would expect that people will consider the model yearas as an important parameter, therefore it important to be able to visually group cars that share similar years. Colors enable us these visual grouping more than other encoding(for example the size of the cirvcle will not enable us the visual grouping). This is also the reason that I made it posible to use a buttons that filter single years. 

It is important to note that even if the price is 0, car with similar years show similar milage. This is also true for 0 milage, car with similar years show similar price. That is another strong indication about our story 'Car Price is Corelated with Model year and Milage'. And this is the reason that I decide to not to omit the "zeros" dots from the charts.

It is important to note here that the circle radius is note encoded to the square root of the number of days, the reason for that is that I wanted to enhance the diferances in the first days of advertisment and reduce the diferances for advertisments that stay for long time. (If an advertisment stay 30  or 31 dayes it is not similar toan advertisment that stay 1 or 2 days).

I use a scatter plot becouse that enable us to inspedt single cars, this is also the reason that I included the information  that pop out on mouse huver and the clickable dots that send the viewer to the advertisment page. That enable the viewer to examine the story further and to go in to more detailes (a bar plot for example will not enable us to go in to more detailes in this case).


Feedback: After aligning the coars along the x and y axis I was quite happy and I show that to my wife but she did not understand what I was talking about, she wanted to be able to see the price and year when mouse huver on the dots. so I introduce that improvment first. 

After I have done that I added the colors and ask my other wife for another opinion again so she told me that she canot understand anything and that is too complicated for her and she canot use it becouse she canot look at the advertisment and teh dots do not tell her anything. so I added the option to click the dots and go to the advertisment. 

Next, after I did that obviesly I wanted to get another opinion so I asking my girl friend for an opinion, but I added the colors becouse I really thoght it would help, she did not really find any intrest in the colors and wannted to know when each car was published. at that point at least she show intrest so I fix that option and she can see now also the publication time as the size of the dots. 


Resource: 
https://google.github.io/styleguide/javascriptguide.xml#JavaScript_Style_Rules
http://d3js.org/
http://stackoverflow.com/



