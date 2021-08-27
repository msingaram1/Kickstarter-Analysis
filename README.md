# Kickstarting with Excel

## Overview of Project
Louise, an up and coming playwright, wants to start a crowdfunding campaign for her new play Fever, but want to make an educated decision on how to go about it.
The following is an analysis on a large set of kickstarter data to determine specifically how different plays fared in funding in relation to their launch dates and funding goals. 

### Purpose
The purpose of this analysis is to give Louise information on how crowdfunding campaigns for plays performed based on launch date and funding goals. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

This chart aggregates the outcomes of whether plays were successful, failed, or cancelled based on when they were launched. 
A quick look at the Theater_Outcomes_vs_Launch chart in the resources folder shows us that the plays launched in the summer seasons (May - July) had the most successful outcomes 
with number of successes trending down as time goes by from May. May is the peak for successful plays. 
There were no canceled plays throughout the dataset and failed plays were pretty consisently around 40 for all months. 

<img width="328" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/36337626/131073108-fdd93acd-28a1-4bf4-9a74-f52ae5c41609.png">

### Analysis of Outcomes Based on Goals

This chart visualizes the percentage of successsful, failed, and cancelled plays based on their funding goal amount. This chart is a lot more dynamic with successes generally decreasing as funding goal increases
with a spike around the 40k mark where as percentage of failed plays increases generally with a dip around the same 40k mark. However, for Louise's purposes, for a funding target of $10,000, the percentage of successful
plays is around 55% which is average when looking at the whole dataset. 

<img width="288" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/36337626/131073100-f3226143-d54f-4415-91b2-936c6879fec4.png">



### Challenges and Difficulties Encountered

The biggest challenge was to implement the COUNTIFS method correctly, at first it was confusing to make sure all the criteria ranges were accurate and I was not sure what the actual function was doing, i.e. why it would have
multiple criteria ranges, but after seeing it for the first column ("Number Successful") it was clear that the function was pulling only the number of cells that met all criteria. Also, I had trouble figuring out how to put images into the readme file. 

<img width="415" alt="COUNTIFS formula" src="https://user-images.githubusercontent.com/36337626/131073134-baffaf8e-3ed8-40dc-aa01-4d1f4463d42f.PNG">

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Plays that launch their campaign in the summer months specifically May to August have the highest success rate. Also, failure amounts stay consisent around the 40 mark. 

- What can you conclude about the Outcomes based on Goals?

In general, successes decrease as funding goal increases and failures increase as funding goal increases. In other words, there is a positive correlation for number of failures and funding goal and an inverse relationship, or negative correlation for 
number of successes and funding goals. However, in the range of 35000 to 45000 there is a spike in successes and a complementary dip in failures. 

- What are some limitations of this dataset?

The dataset is almost too large for what Louise is looking for, which is just plays. Also, excel was slowing down and crashed multiple times due to this.
Additionally, it would be preferrable to have the source for how it was crowdfunded to analyze which crowdfunding sources had more success to give Louise an even 
more informed decision. 

- What are some other possible tables and/or graphs that we could create?

We can create a Outcomes based on Country, Outcomes based on category, Launch dates vs Funding Goals, Funding Goals vs Country, etc. 

