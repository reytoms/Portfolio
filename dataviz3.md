# __Step one: Find a data visualization__

As a huge fan of the Olympic Games, I was particularly interested in working with the Tokyo 2020 Olympics visualization. I recall during the olympic season this year, I came across a visualization of the medal tally which was neither visually appealing nor easily interpretable. Before I could make sense of the numbers presented, the screen already transitioned to the next. I had to then find other sources for the same data, or wait until the channel displayed the visual again.

Another reason I chose this data is because it is fairly recent. I trust that the viewers of my visualization would enjoy refreshing their minds about the success of the recent Summer Olympics.

Below is a screenshot of the original data visualization (I am attaching just the top few rows of the visualization to give an idea):

<img width="681" alt="Screen Shot 2021-11-09 at 11 27 32 AM" src="https://user-images.githubusercontent.com/92896969/140964288-71493b9b-3c4e-4ba3-a0de-c413d274fd39.png">

Link to the visualization:
![2020 Tokyo Olympics medal count: USA tops China in gold, silver, bronze and overall medal totals](https://www.cbssports.com/olympics/news/tokyo-olympics-final-medal-table-usa-leads-in-in-gold-silver-bronze-and-overall-with-more-than-100-medals/)

# __Step two: critique the data visualization__

Summary of the critique:

I would consider the intended audience of this visualization as the CBS channel viewers inc;uding, but not limited to the followers/fans of the Olympic Games, delegates from the participating countries, and the athletes. The visualization though useful, is not very intuitive or appealing. 

The information is presented without discrepancies or much confusion as it includes required information in terms of the medal counts for the different countries. I would also like to highlight that "no medal" is denoted by a “0” rather than a blank space. A blank space would open room for confusion. I did not notice any incorrect information or inaccurate comparisons made. However, I had to confirm this based on my research across other websites. There were no references indicated in the chart. 

In terms of intuitiveness, though the data is not too hard to understand, the visualization is not inviting or visually intuitive. 

Perceptibility, Aesthetics and Engagement are the sections where I would give a comparitively lower rating. 

If the comparison was just between China and USA (as the title states), then I would give a higher perceptibility rating because the count of medals for both countries are topping the list. However, considering that the intended audience are fans of Olympic Games in general (not limited to USA and China), I would give a relatively lower score because the title is somewhat inaccurate/misleading. Viewers who are not interested in the comparison between China and USA, might not care about the visualization. Furthermore, if a viewer was interested only in the numbers of a particular country, they would have to scroll all the way up again because as the chart rolls lower the colomn titles are hidden. To elaborate, a person looking at the numbers for Qatar simply reads the numbers 2-0-1-3. The length of the chart does not indicate what these numbers imply. This could leave the viewer confused about what the number in each column represents unless he scrolls back to the top and reads the title again. 

In terms of aesthetics and engagement, the visualization does not include preattentive visual features. I was distracted by flag icons rather than the medal tally. In addition, the data is not easily comparable from the chart (too many numbers). In case a viewer wants to know the order of countries by the number of gold medals alone, the visualization is not user-friendly (not interactive).

Noting these critique points, I would like to wireframe a new visualization for the same data. I would like to revisualize the data to boost the rating in emotive category that includes the aesthetics and engagement criterias.
 

# __Step three: wireframe a solution__

To strenghten the emotive aspect of the visualization, I would like to incorporate the following in my wireframed solution:

a. Visual representation of the medal counts denoting the medal type (Gold/Silver/Bronze) in a single view 

b. Sorting options for both the medal types as well as the total count

c. Change of title to highlight the key result of the data, rather than comparison between just 2 countries


![Sketching](https://user-images.githubusercontent.com/92896969/140599340-7d392805-a1ee-41cb-bda7-ab7c3243b1a4.jpg)

 
Note: 

a.	The sketch is not drawn for all countries. The goal was just to give an idea about how the data could be visualized. 

b.	Content not written neatly and clearly. I will fix this in the final visualization by printing the title and other written data.

# __Step four: Test the solution__

Below are response from different audiences:

**Question 1: Can you tell me what you think this is?**

 Friend 1: Is this a medal tally for some games? Until I saw the title, I was confused which games this was referring to.
 
 Friend 2: Medal tally for the 2020 Tokyo Olympics.

**Question 2: Can you describe to me what this is telling you?**

 Friend 1: It tells me that USA, China, and ROC topped the Olympic games 2020.

 Friend 2: It tells me that the medal counts are arranged in descending order and tells me the count of each medal type.

**Question 3: Is there anything you find surprising or confusing?**
 Friend 1: I was keen on knowing about a specific country (Australia) which was not immediately visible. I scrolled my eyes through the country list till I found Australia.
 
 Friend 2: The shades used for gold and bronze look similar

**Question 4: Who do you think is the intended audience for this?**
 
 Friend 1:  The people who follow The Olympics (fans)
 
 Friend 2: Olympic fans and Team officials from the participating countries.

**Question 5: Is there anything you would change or do differently?**

 Friend 1: I would include the sorting buttons for the country column as well

 Friend 2: I would increase the contrast between gold and bronze to make it more distinct.

## __Take away:__

The feedback was very valuable to me. Though I noticed that the reviewers were not confused by the visualization, there were some key points that highlighted ways by which I could better the visualization. 

Key changes to be made:

I have decided to add a sorting button for the “Country” column as well. I will also try to use an appropriate palette to distinguish the gold and bronze better. Personally, I am not very content with my title. I feel like it is too wordy so I would like to change that as well.

# __Step five: Build your solution__


The final step is to incorporate the critique points and revisualize the data digitally. Below is the revisualized data.









## __Summary:__


At first it was a little challenging to find the right platform that could display the data, but eventually I learnt that it was possible from Tableau. I used the Text tables chart type to display the data.

a. I included the sum of gold, silver, bronze and total medals to the "Measure Values" category.

b. The country names were added as rows to the visualization.

c. As I am not very familiar with the software, I spent sometime trying to understand how I could demonstrate the medal icon and use different colours to denote the different medal types. I was able to achieve this by choosing the "Use Separate Legends" option available in the "Measure Values" drop down menu. This allowed me to choose different colors for the gold, silver, bronze and total columns.

d. I used the following colour palette: Hex Color #D4AF37 (Gold), Hex Color #A8A9AD (Silver), Hex Color #A97142 (Bronze), Hex Color #FFFFFF (Total). I used a white shade for sum of total as it does not signify any specific color.

e. I used the center align text option for the 'Marks', to indicate the medal count within the circles that denote the medal type.

f. Considering the review feedback, I included a sorting option for all columns.

g. I made sure all my fonts and font sizes are relative and uniform to make the visualization look clean.

h. I gave a title that clarifies the key result derived from the visual. The title reads, "Olympics Tokyo 2020: USA leaps ahead of the medal tally"

i. Noting the medal icon colors are darker especially for the bronze, I bolded the numbers within the icons for clarity. I noticed that this left the counts stand out from the rest of the data, so I bolded all the text to make it uniform. I decided to do this because I consider all data in the chart of equal value - country names as well as count of each medal type and total.

j. I used a font size of 11 for all the column headers and a font size of 10 for the country names and the medal counts.

## __Challenges faced & Future Work__

a. I could not add the flag icons for the country names. I trust it would be good to have that included because it could add to the visual intuitiveness and aid those who cannot read the english language. I would like to consider this as part of my future work for the visualization.

# __References__ 

1. Sports Staff, CBS. “2020 Tokyo Olympics Medal Count: USA Tops China in Gold, Silver, Bronze and Overall Medal Totals.” CBSSports.com, 8 Aug. 2021, www.cbssports.com/olympics/news/tokyo-olympics-final-medal-table-usa-leads-in-in-gold-silver-bronze-and-overall-with-more-than-100-medals/.




