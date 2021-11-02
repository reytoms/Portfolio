The General government debt-to-GDP ratio is the gross debt of the government as a measure of GDP percentage. This ratio is an indication of the government finances. The range of values over the years is a telling tale about past govermental drawbacks in the country.

We will visualize this data for different countries using the various data visualization methods.

### __Government debt bar chart (Year: 2018)__ ###


<iframe src="https://data.oecd.org/chart/6vmX" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6vmX" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>








### __Grid of line charts__ ###


This chart represents each country individually, reflecting the ratio for the years from 1995 to 2020. The chart also distinctly indicates the index (ratio value) for year 2020 with a bigger dot as compared to the other data points.

<div class="flourish-embed flourish-chart" data-src="visualisation/7678272"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

**What do I like about this chart:**

a. The chart has a title indicating the result of study for the year 2020: Japan has the highest government debt-to-GDP ratio in 2020

b. Eye travel is minimal to find the value of data across the years: Value is marked on the line curve

c. The axes are labelled to indicate the data type

d. Usage of grey colour for axes (gridlines) to mute the overall noise from the chart bars/backgroud

**What would I like to change about this chart:**

a. The chart does not compare all countries simulatenously. The viewer has to make a study for each country individually, and then manually identify the most debted or least debt countries. I would like to make a chart that makes it easy for viewers to derive information/results about the data from the visuals.

b. Despite having a header, the visuals do not easily/quickly complement it. In other words, I need to look at the visual for a long time to agree on that result (Japan owes the highest debt in 2020).

c. There is a lot of information on this chart which could be eliminated to enhance clarity of the visual (moderate the presentation depepnding on the audience). For instance, I might not need to show the data for all countries if my viewers are only interested to know about Asia. In addition, the time ranges from 1995 to 2020 which might not be necessary. I could limit these depending on my audience/scope of presentation.

d. Though eye travel is reduced because the values are denoted on the line graph, the data seems to be cramped. This makes it difficult to identify to which dot the value corresponds. 

e. The chart looks too comprehensive with a lot of data that does not indicate any key result.

Overall, on a scale of -10 to 10, I would rate this dataviz a score of 4 for both, design execution and contextual awareness. 

### __Third Data Visualization__ ###


Incorporating points from "What I would like to change" about the previous visualization, I created 2 bubble charts to visualize the data more clearly. 

a. <div class="flourish-embed flourish-scatter" data-src="visualisation/7691484"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

First, I grouped the dataset by categorizing the different countries and grouping them into regions. I calculated the average index across all countries in each region and assigned the value to that particular region. I made a bubble chart using complementary colours to represent the different regions (Oceania: #FFE203, Europe: #781EA8, Asia: #FC6500, Americas: #2889C6, Africa: #008A2E). I created my own color palette from Adobe Color. I included a title on what the data is about, and highlighted the 1 region I wanted to focus on (This was based on the assumption that my viewers were interested in Asia). The title reads, "GOVERNMENT DEBT-TO-GDP RATIO ACROSS REGIONS: Asia ranks No. 2 following The Americas in 2020". I also added a subtitle decribing how the ratio was calculated. 

This method allowed me to incorporate all the data and distinguish them using colours that did not have any relation indicating that they are categorical data. Moreover, including all the data in a single view of pane allowed my viewers to infer information and make meaningful comparisons across the regions. 

**What was I able to interpret from this chart:**

I was able to infer that the government debt-to-gdp ratio in 2020 was highest in the Americas, followed by Asia. The ratio for other regions are comparable and not significantly far away from Asia in the year 2020. I also noticed that out of all the regions across all the years. (1995 to 2020), the highest average index value was recorded for Asia (value=140.8 ) in the year 2000.

b. <div class="flourish-embed flourish-scatter" data-src="visualisation/7692158"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Considering that my audience are interested in information about Asia, I created another visualization focusing on countries across Asia alone. I chose to highlight the data for Japan and noticed that it remained a constant leader in the debts over the last 25 years. I highlighted this in the chart title, "JAPAN REMAINS THE HIGHEST DEBT COUNTRY IN ASIA OVER THE LAST 25 YEARS", and gave the colour pink (Japan: #E7086E) to Japan, leaving the other countries in grey (#A9ADB0) to focus my viewers attention to Japan. 


## __Summary__ ##


The reason I chose a bubble chart was because I wanted to include atleast 3 variables in a single view - the regions, values (ratio of debt-to-gdp), and the year. I liked that the bar chart was arranged in the order of increasing ratio which aids the user to interpret which country has the highest/lowest ratio, but the chart does not give comparable information for each country across the years. The visualization is limited to one year at a time. The second, grid of line charts did not include the data for all regions into a single chart. Perhaps, this could be made possible, but I would imagine the chart to appear noisy. In other words, even though I was able to read the information from both the bar and grid of line chart, I was unable to deduce anything valuable or make quick comparisons across regions/yeats just by looking at the visualization. These drawbacks could limit me from effective decision making.

I trust that the purpose of visualization is to tell a meaningful story using data and visuals, wihtout the use of too many words or a cramped visual. The bubble chart helped me achieve that. In summary, it conveys a clear overall result and the corresponding values such as the index number (or other more intricate details) can be found by hovering the cursor on the bubble of interest. Due to the vast data set, to avoid a noisy visual, I did not include the ratio values in the immediate view of visualization. However, the values pop up for a viewer who might be interested in the numbers. I also grouped the data to regions and further to countries within a region to limit the number of variable categories (This grouping was based on my assumption that the target audience is interested in data about Asia. I could modify it depending on my target audience.)

The colors, minimal words/labels in the visual, and a title that summarizes the result makes it more appealing and inviting to the audience. It also contributes to the ability in comparing data, to tell a story and in effective related decision making.

I used two preattentive attributes such as colour and size for visual encoding.

The use of various contrasting colours to represent the regions allowed me to portray that the data is categorical and not relational to one another. Moreover, with the bubble size altering based on the value (ratio), the viewers are able to interpret/compare the data for better understanding. Personally, the third visualizing (section b) helped me understand that Japan has significantly remained higher than other countries in the government debt-to-gdp ratio. The value corresponding to Japan has also linearly progressed over the years. This is inferred from the bubble size for Japan that increases with each year. The distinct colour used for the corresponding visual made it stand out from the other countries. 

With the first two charts I was not able to infer the same information.


## __Future work__ ##

a. I would like to find a way to control the opacity of the bubble colours depending on the value it denotes. That is, to change the intensity/saturation of colour based on the index value.

b. I would re-order the regions/country in an alphabetical order. With the chart for countries in Asia, I would place Japan in the center of the y-axis rather than the last row (I learnt that to do so, I have to re arrange my data set in excel placing Japan in the center of the list of countries for Asia)

## __References__ ##

OECD (2021), General government debt (indicator). doi: 10.1787/a0528cc2-en (Accessed on 01 November 2021)

Adobe. “Color.” Adobe.com, 2019, color.adobe.com/create/color-wheel.



