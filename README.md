
    👋 Hi, I’m Ashutosh Pathak
    👀 I’m interested in R & Python
    🌱 I’m currently learning Data Science and Analytics
    📫 How to reach me ... you can reach me on ashutosh.pathak00@gmail.com

# Bike Share Project

## Introduction

Welcome to the Cyclistic bike-share analysis case study! In this case study, we will perform many real-world tasks of a junior data analyst. We will work for a fictional company, Cyclistic, and meet different characters and team members.In order to answer the key business questions, We will follow the steps of the data analysis process: ask, prepare, process, analyze,share, and act.

## Scenario

You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations.

### Characters and teams

● Cyclistic: A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself
apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with
disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.

● Lily Moreno: The director of marketing and your manager. Moreno is responsible for the development of campaigns
and initiatives to promote the bike-share program. These may include email, social media, and other channels.

● Cyclistic marketing analytics team: A team of data analysts who are responsible for collecting, analyzing, and
reporting data that helps guide Cyclistic marketing strategy. You joined this team six months ago and have been busy
learning about Cyclistic’s mission and business goals — as well as how you, as a junior data analyst, can help Cyclistic
achieve them.

● Cyclistic executive team: The notoriously detail-oriented executive team will decide whether to approve the
recommended marketing program.
 
 
## About the company


In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime. Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments.One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are
interested in analyzing the Cyclistic historical bike trip data to identify trends.

### Ask

Three questions will guide the future marketing program:

 1. How do annual members and casual riders use Cyclistic bikes differently?
 2. Why would casual riders buy Cyclistic annual memberships?
 3. How can Cyclistic use digital media to influence casual riders to become members?

Moreno has assigned you the first question to answer: How do annual members and casual riders use Cyclistic bikes
differently?

You will produce a report with the following deliverables:

 1. A clear statement of the business task
 2. A description of all data sources used
 3. Documentation of any cleaning or manipulation of data
 4. A summary of your analysis
 5. Supporting visualizations and key findings
 6. Your top three recommendations based on your analysis

## Prepare
 * You will use Cyclistic’s historical trip data to analyze and identify trends.
 * Download the previous 12 months of Cyclistic trip data  [here](https://divvy-tripdata.s3.amazonaws.com/index.html) , I have used July 2021 to June 2022 data.  
 * This is public data that you can use to explore how different customer types are using Cyclistic bikes.
 
### Limiation

Data-privacy issues prohibit you from using riders’ personally identifiable information. This means that you won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes.
 
 (Note: The datasets have a different name because Cyclistic is a fictional company. For the purposes of this case study,the datasets are appropriate and will enable you to answer the business questions. The data has been made available by Motivate International Inc. under this [license](https://ride.divvybikes.com/data-license-agreement).)
 
### Is Data ROCCC?

A good data source is ROCCC which stands for Reliable, Original, Comprehensive, Current, and Cited.

 1. Reliable - HIGH - I trust that I’m getting accurate, complete and unbiased information that’s been vetted and proven fit for use as the data comes from a real-world source, and the only manipulation done to it is anonymization.
 2. Original - LOW - The data comes from a third-party provider. (Divvy Bikes)
 3. Comprehensive - MED - The data can provide good answers to some of the business questions, and only hints to others.
 4. Current - HIGH - The data is uploaded after the end of each month, and it serves the purpose of finding trends and user behaviours as it gives a historical overview.
 5. Cited - HIGH - The data was created by a credible organization, it’s real world data, and recommended for the use case by Google

## Process

 * We have Used R language to process our data and merge different 12 files into 1.
 * We have checked for our data consistency 
 * After Merging we have cleared unwanted data chunks to clear our memory.
 * Inspected our data for any kind of error and discrepancy.
 * We have added few more columns in our data to get the date, month, day and year  
 * We have calculated Ride length in minutes 
 * We further added Months, Season and Time of the day to get in-depth analysis.
 

## Analyse 

 * In analyse phase we have calculated  Mean, Median, Max and Min ride lenght.
 * We have also compared the ride lenght with rider type i.e casual rider and member

## Share

 * In this phase we are sharing our data findings with the help of visualization.


## Act

In this step, We will be delivering our insights and providing with recommendations based on our analysis. To do that, we will be revisiting the business questions.

1. How do annual members and casual riders use Cyclistic bikes differently?
 * Members do more bike rides for shorter periods.
 * While Casual riders do less bike rides but often their rides are longer.
 * Casual riders tend to do more bike rides in the spring and early summer months. 
 * Members tend to do less bike rides in the winter months, with the exception of February.

2. Why would casual riders buy Cyclistic annual memberships?
 * Based on the data insights, members do shorter bike rides it means its mostly work related.
 * This leads us to think that a membership gives users the comfort to travel by bike regardless of the distance and amount of trips.
 * Whereas we have found that casual rider take less rides but for longer duration. This could mean that non-members are taking longer trips i.e planned trips, leisure rides. An annual membership can get them extra perks for being member.

3. How can Cyclistic use digital media to influence casual riders to become members?
- Casual riders are most active on Fridays, Saturdays and Sundays in all months, and do longer trips. Hence, the marketing team can aim to promote the annual memberships more on these days. Also, the longer trips might mean that casual riders rent the bikes for planned outdoors weekend activities. Hence, the marketing team should be lead by this narrative in their promotional campaigns.

## Recommendation 

 * Some time limitation to be initiated after which extra charge would be levied for casual riders.
 * New member membership rebate program on annual membership.
 * Various types of membership can started be like weekly and monthly, for those who do not wish for annual membership.
 * Various offers in other franchises for being the loyal member.
 * Priority to members during peak hours.



