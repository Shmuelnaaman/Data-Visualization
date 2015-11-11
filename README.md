# Data-Visualization
Summary:
The data include second hand cars for sale that were published in craiglist. Each dot on the scatter plot represents the information of a single car. The Price [$] as the X-axis, the Odometer [Km] as the Y-axis, the model year as colors and the number of days since the advertisement was published as the size of each dot. The main objective of the chart is to reveal the relation between the price of the car the year and odometer reading. The interesting story about the data set and the explanatory chart demonstrate that very nicely as a short story: Price is positively correlated with years and negatively correlated with mileage. Clicking on early years, revealed low price cars with high mileage and as we click on later years the dots slide down right to represents high price cars with low mileage. Another side story that the chart tell us is the no corelation between the duration of advertisment with the other features. The interpetation of this result indicate that as long that the car price and milage is in the reasnable range, that will not be what make people to buy the car. 

Design: 
The most important features in the data set are the price and Odometers, therefore I choose to position them along the x and y axis.

The color encode the years, the reason for that is that we would expect that people will consider the model yearas as an important parameter, therefore it important to be able to visually group cars that share similar years. Colors enable us these visual grouping more than other encoding(for example the size of the circle will not enable us the visual grouping). This is also the reason that I made it posible to use a buttons that filter single years.

It is important to note that even if the price is 0, car with similar years show similar milage. This is also true for 0 milage, car with similar years show similar price. That is another strong indication about our story 'Car Price is Corelated with Model year and Milage'. And this is the reason that I decide to not to omit the "zeros" dots from the charts.

It is important to note here that the circle radius is note encoded to the square root of the number of days, the reason for that is that I wanted to enhance the diferances in the first days of advertisment and reduce the diferances for advertisments that stay for long time. (If an advertisment stay 30 or 31 dayes it is not similar toan advertisment that stay 1 or 2 days).

I use a scatter plot becouse that enable us to inspedt single cars, this is also the reason that I included the information that pop out on mouse huver and the clickable dots that send the viewer to the advertisment page. That enable the viewer to examine the story further and to go in to more detailes (a bar plot for example will not enable us to go in to more detailes in this case).

Feedback: After aligning the cars along the x and y axis I was quite happy and I show that to my wife but she did not understand what I was talking about. She suggested make it possible to see the price and year when the mouse hover on the dots. so I introduce that improvement first.

After I have done that I also added  the colors and ask my other wife about her  opinion. At that point I did not wanted to ask my first wife she was way too bussy for me and I did not thoght she will have any good ideas any way. But my secound wife was even less understanding and told me that she would want to investigate even further in to more details. Since I could not include much more information on the chart I decided to dd the clicable option that send you to another page with all the details that are aailable. 

Next,  I wanted to get another opinion but this time I decided to not ask my wifes so I went to visit my girl friend and ask about her opinion. At that stage I added the colors because I really thought it would help to visualise the groups of years, But she did not really find any interest in the colors becouse she cant distingush between colors very well. So she ask me to add the option that I can display inly one year at a time. that was the reason for adding the clikable buttons  for each year. 

Resource: 
https://google.github.io/styleguide/javascriptguide.xml#JavaScript_Style_Rules
http://d3js.org/
http://stackoverflow.com/



