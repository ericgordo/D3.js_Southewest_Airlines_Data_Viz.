# D3 Data Visualization 
## by Eric Gordon
This Project is my first attempt at using D3 to create a data Visualization. 

[Click Here to see the Final Data Visualization in Action](http://bl.ocks.org/ericgordo/raw/537f40a3d71dad52cee52813e3a57b8a/)

### Summary 
This project tries to show the numerical difference at which Southwest Airlines seems to operate versus all major United States 
Airline companies. Not only does Southwest have more flights annually than every other carrier, but it also seems to be increasing 
in the future, with the potential of gaining a larger advantage over the competition. The data available for public use sadly 
only went up to 2008, however this data was enough to show the shocking disparity of the number of commercial Southwest flights,
versus all other carriers. The final version of this visualization is labeled index.html.

### Design 
To make this point clear, I decided upon a graphic line chart, which I felt really helped show the two major take away points
from my data analysis. First, that Southwest seems to be increasing in the number of flights they are operating year after year. 
Additionally, Southwest seems to operate many more flights any other American based airline, which was a surprise to me. I wanted to 
show both this change over time and the comparison of of different airlines, so I felt that this line graph was the best option to 
show off my analysis. A major priority was learning to code with d3.js, so I worked exclusively in this language without wanting to 
incorporate other applications that are more user friendly. However I was able to implement some interactivity with information 
“toolips ”when you hover over the points, and the company selection buttons, which I enjoyed coding. Most changes in the design were
made to help improve clarity, make my findings more clear, and push the point across that Southwest clearly flights more annually
than any other carrier. These designs were made in consideration with several pieces of feedback I heard from others.

### Feedback 
#### Feedback 1
The first person who looked at my plot recommended that I remove a lot of the excess plots because it was hard to see all of the carriers at the same time. He said, "yes it is easy to see Southwest above all of the other companies, but it is hard to compare others like JetBlue and American Airlines, I wish I could do that." 

-Thus I decided to make the interactive buttons on the side of the chart, so that plots could be selected and deselected.
#### Feedback 2
After the buttons were added, the second individual recommend to start off with less of the 
charts on the plot. "I like that I can get rid of some of the lines, but there are so many of them. I don't want to do all of that work."

-With this feedback I decided to make the starting plot only have Southwest Airlines, instead of starting with so many plots.

#### Feedback 3
Another individual liked the overall chart, but wanted the buttons to also help with the color coordination. 

-I therefore added the color fill to each button, so when it is clicked, it filled with the same color as the line on the plot. 

#### Feedback 4
A final individual recommended that I start the plot with some sort of comparison, so that the plot at least initiated with two lines not just one. Additionally, this same individual stated that it would be better to make the carrier buttons more noticeable and obvious.  


With this feedback, I made two crucial changes. 

-I outlined each button with a black border, to try to make them more clearly buttons. 

-I created a record for “Average” so that when the chart loaded, Southwest was compared to the average of all carriers, thus showing the large gap, but not overcrowding the map. 

## Resources 
#### General d3.js help and documentation: 
https://leanpub.com/D3-Tips-and-Tricks/read

https://bost.ocks.org/mike/ 

http://chimera.labs.oreilly.com/books/1230000000345/index.html 

https://d3js.org/

https://www.udacity.com/course/data-visualization-and-d3js--ud507


#### Inspiration with Buttons:
http://bl.ocks.org/d3noob/5d621a60e2d1d02086bf

