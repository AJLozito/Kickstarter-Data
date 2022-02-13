Louise’s Production



Overview of Project

     The purpose of this project is to determine the type of production endeavor Louise should choose by evaluating past launch dates and fundraising goals within a set of data provided by Kickstarter.


Analysis and Challenges

     I began by putting the data into a table in order to make my references more simplistic. Next, I set up specific pivot tables to measure the Theatre outcomes based on their associated launch dates. I subsequently built a chart to illustrate the months that had the most successful outcomes, which allowed me to assess what the optimal month would be to start her project. I then built a sub data table with COUNTIF functions. This allowed me to build ranges to reflect the funding “sweet spot”. Finally, I built a chart based on this sub data table to extrapolate the outcomes against their original goals. Below are the associated screenshots:

Kickstarter Data Table
![image](https://user-images.githubusercontent.com/96176817/153769838-3ddd9d09-791d-4167-8bf4-d8422c60ffaf.png)

Theatre Outcomes by Launch Date
![image](https://user-images.githubusercontent.com/96176817/153769850-6518cc63-c7a2-4c86-8a41-01df99ebb009.png)

Outcomes based on Goals Sub Table
![image](https://user-images.githubusercontent.com/96176817/153769867-5fb742b3-de79-4139-a665-3b08c3ccb219.png)

Outcomes_vs_Goals.png
![image](https://user-images.githubusercontent.com/96176817/153769879-68745515-a0c2-48ff-8c39-6647b40abfa7.png)

     The only challenge I experienced was when I put my Outcomes_vs_Goals.png chart together. I initially set the data in my sub table to the pledged amount, which gave me a very strange looking chart. I reached out to the Teaching Assistant (Malcolm McCabe), and he quickly pointed out that I was making an incorrect cell reference. Once I updated that part, my chart perfect reflected the chart in the Deliverable 2 Instructions.


Results

     There are two conclusions I made about the Theater Outcomes by Launch Date. First, the overall success rate hovered around 61%, and only ranged from 49% to 67%. This means the variability by month was minimal. Secondly, I would launch my project in May because it has both the highest total number of success projects and the best propensity to achieve a successful outcome.

     One conclusion drawn from the Outcomes based on Goals is that a successful project is most likely going to have a fundraising goal of less than $5,000. This conclusion is validated by that range having both the highest success rate (about 67%) and the most voluminous amount of data to back up that percentage (this range represented about 69% of this subset of data).
     
     While this analysis was thorough based on the amount of data presented, it was still a small data set. There were less than 3,000 total results to be analyzed, thus much more robust data sets probably exist, and could provide further detail to generate a more accurate conclusion. Based on the data I used, the only other metric I’d consider is “Days to Fund”. This may enable Louise to understand how long it takes to raise her capital.
