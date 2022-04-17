# Analysis of Kickstarter Campaigns
## Overview of the Project
The purpose of this project is to compare the results of theater and play fundraising campaigns based on their launch dates and fundraising goals. Our client, Louise, produced a play, _Fever_, which came close to its fundraising goal in a short amount of time.  I was tasked with providing her with the relationship that different campaigns had based on their launch dates and funding goals.

## Analysis and Challenges 

### Analysis of Outcomes Based on Launch Date

To analyze the dataset, I used Pivot Tables and created Pivot Charts within Microsoft Excel.  With using Pivot tables, I was able to filter the data using a Parent Category "theather." By doing this, I will only pull and use data that falls within that catergory for the Pivot Chart created.  I then organized the data based on month and seperated the results based on the outcome: How many plays were successful, failed, or canceled.

<img width="342" alt="Pivotchart1" src="https://user-images.githubusercontent.com/103154070/163727015-c38c0de5-e875-4b81-9b51-788bc3d4dfe9.png">


With this information, I created a Pivot Chart that provided imagery around the results filtered. 

![Theater_0utcomes_vs_Launch](https://user-images.githubusercontent.com/103154070/163727026-e6d2421f-7400-4469-a5e4-0d3daf5b9285.png)

From this chart, we can clearly see the trends month over month for the year of plays that were produced.  During the months of Februaury, May and October we can see a spike in successful plays.  However, during the month of May, the spike in successful plays is greater than the other months due to their being more production of plays over the months of May and June.  Although there were more plays that were produced during this time, we still can see that the amount of successful plays greatly surpasses the amount of unsuccessful plays during this time.  So what does this information tell us? It tells us that overall, plays had the highest success rate in May.

### Analysis of Outcomes Based on Goals 

To find the outcomes based on goals, there was a little more pre-work needed to find these results.  The first step was to create a table that would provide the percentage breakdown of successful, failed and canceled plays in relation to their goal.  To do this, I created a series of "Count-If" statements from the Kickstarter datatset filtering only those that fall in the subcategory "Plays."

<img width="705" alt="goalschart" src="https://user-images.githubusercontent.com/103154070/163727467-163d6e2c-c2d8-4e4b-8cab-16d6cceabe0b.png">

From this data, I created a line graph that would provide a image supporting the Percentage of plays that were either successful or failed with respect to their goal for the project.

![Oucomes_vs_Goals](https://user-images.githubusercontent.com/103154070/163728014-b8e41a14-c17b-4478-9be3-59a9c7e9b1f0.png)


The graph shows us that when the goal was within the range of $29999 to $44999 there was a steady increase in the amount of successful plays that were produced.  Also, goals that were greater than $44999 appear to have a greater chance of failing.  

### Challenges or Difficulties Encountered

The process of creating the data used for the Outcomes Based on goals chart was very time consuming.  Each cell had a unique "Count-If" formula that had to be input in order to calculate that number accurately.  I had to be very cafeful and thorough when entering each input.  I did not find a more efficient method to doing this process.  Additionally, when created my line graph, it was not as simple as when using Pivot tables.  My legends for "Percentage Failed" and "Percentage Successful" did not auto-populate, so I had to do a bit of trial and error to problem solve.  


## Results 

### What are two conclusions you can draw about the Theoter Outcomes by Launch Date?

1. There is a positve increase in the amount of successful plays produced from March to May, with May being the most successful month.
2. From May to September there is a consistent decrease in the success of plays produced.  Although there is a slight increase in success between Septmember and October, the downward trajectory continutes through December.

### What can you conclude about the Outcomes based on Goals?
Plays that had lower fundraising goals tend to be more sucessful. The greatest success is found with those who have a fundraising goal that is less than $1000, with a 76% success rate.

### What are some limitations of this dataset?

There are actually quite a few limitiations within this dataset.  There is a lack of information around the demographics of the population that was analyzed.  For example, we do not know how realtable the context of the play was given the location that the play was shown.  Also, we do not have information on the marketing campaigns that were used to promote the plays in a given location.  There is also a limitation around the type of currency used.  Each country provided goals and pledged amounts based on that country's currency.  In order to have a more accurate idea of these numbers, we would want to find a way to assure that the currency exchance rate is synomonous amoungst all countries.

### What are some other possible tables and or graphs that we could create?

It could be helpful to create a graph that would show the amount of backers needed to drive successful results.  Using the dataset, we could take a deep dive into the amount of backers aligned with the average amount donated.  It also may be helpful to create a graph or table that would show us success rates based on country.  This could help with determining which types of plays are more sucessful in which areas.
