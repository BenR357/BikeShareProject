# Bike Share Project

## Project Description
The project involves a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The team aims to understand how casual riders and annual members use Cyclistic bikes differently to design a new marketing strategy to convert casual riders into annual members. The recommendations must be backed up with compelling data insights and professional data visualizations.

<h2>About the Company</h2>
Cyclistic launched a successful bike-share offering in 2016. The program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Moreno believes that maximizing the number of annual members will be key to future growth. Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members.
<br />

<h2>Programs and Languages Utilized</h2>

- <b>Excel</b> 
- <b>SQL</b> </b> <b><a href="https://docs.google.com/document/d/14r6P8wkU_-a02wb2xuPyjLq6n_H4Z1TJn_Jbe5ztmgw/edit?usp=sharing">link to scripts and analysis </b>
- <b>Tableau</b> <b><a href="https://public.tableau.com/views/ride_share_short/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link">link to Tableau </b>
- <b>Google Slides</b> <b><a href="https://docs.google.com/presentation/d/1lKEfvHA1A0PwmzfiniiFrlW4KaJ01p5mnufWade_g_Y/edit?usp=sharing">link to presentation </b>


<h2>Walk-through Summary:</h2>
(Cyclistic is a fictional company and the data has been made available by Motivate International Inc. under this <b><a href="https://ride.divvybikes.com/data-license-agreement"> license</b>.)

<br /> <br /> </b>
 <h3>EXCEL</h3>
<p>I secured the original data by storing it in my password-protected Google Drive. I then made copies of all the files and added a suffix of ‘…v1’ to each one. I opened each file in Microsoft Excel to review the data and determine what type of information was available. During this process, I added several columns to the data:
<br /> <br />a. "ride_length" which is calculated by subtracting the "started_at" column from the "ended_at" column (=D2-C2). 
 <br /> <br /> b. "day_of_week" which is calculated by using the "WEEKDAY" command (=WEEKDAY(C2,1))
 These formulas were copied down to include all rows of data for each spreadsheet. </p>
 <br />
 
 ![image](https://user-images.githubusercontent.com/129348678/229319137-483f5ede-05cb-4863-ac10-4c0cb79fb396.png)

 <h3>SQL</h3>
After transferring the data to SQL, I conducted a thorough analysis and extracted valuable insights on emerging trends. This included cleaning the data, comparing average ride time by rider type, comparing total rides by rider type, and finding which day of the week has the most rides by rider type. To see a detailed walkthrough for SQL along with the scripts, follow this <b><a href="https://docs.google.com/document/d/14r6P8wkU_-a02wb2xuPyjLq6n_H4Z1TJn_Jbe5ztmgw/edit?usp=sharing">link</b>.

![image](https://user-images.githubusercontent.com/129348678/229322558-87552c81-3925-4ec0-81ed-8ba1f227c24e.png)

![image](https://user-images.githubusercontent.com/129348678/229322631-9841bb15-2ecb-4bbb-ab44-cde8c417cc70.png)
<br />
<h3>Tableau</h3>
Following data cleaning and analysis using SQL, I leveraged Tableau to create several tables and visualize the data in various ways. While designing the tables and adjusting the filters, I uncovered additional insights that I had not previously noticed. This <b><a href="https://public.tableau.com/app/profile/benjamin5615/viz/ride_share_short/Dashboard1">link</b> to my Public Tableau dashbord shows some of my observations. 

![image](https://user-images.githubusercontent.com/129348678/229315371-b4d2670c-c8df-459b-b50f-7053295820ad.png)

<h3>Presentation</h3>
Drawing on the insights obtained from Excel, SQL, and Tableau, I synthesized the data into a clear and compelling narrative using a Google Slide presentation. The presentation highlights the key trends and patterns in the data, and includes detailed visualizations and analyses to support the conclusions drawn from the data. Additionally, I provided actionable recommendations for stakeholders based on the insights gained through the analysis, in order to inform data-driven decision-making. Follow this <b><a href="https://docs.google.com/presentation/d/1lKEfvHA1A0PwmzfiniiFrlW4KaJ01p5mnufWade_g_Y/edit?usp=sharing">link</b> to see the full presentation.

<h3>Summary and Recommendations</h3>
<ul>
<li>Offer discounted rates for longer-term memberships: Since casual riders tend to take longer rides, the company can offer discounted rates for monthly or yearly memberships to encourage them to become members. This will incentivize them to ride more frequently, and the lower cost may help them justify the upfront expense.</li>
<li>Increase marketing during peak casual rider months: Since casual ridership is highest during the summer months, the company can increase its marketing efforts during this time. This can include targeted social media ads, promotional offers, or partnerships with local tourism organizations to attract more casual riders.</li>
<li>Develop a loyalty program: Members already receive perks such as lower rates and priority bike access, but the company can develop a loyalty program that rewards frequent riders with additional benefits. This can include things like free ride credits, exclusive access to events, referral incentives, or even partnerships with local businesses for discounts. By offering additional incentives to ride, casual riders may be more likely to become members.</li>
<br />

***Further research is needed to have a better understanding of rider habits, such as tying rides to a specific member. Our assumption was that the high number of casual and member rides was coming from a high number of riders. This could be further analyzed if we have a rider ID linked to each ride so we could see how often each casual and member use our service.***


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
