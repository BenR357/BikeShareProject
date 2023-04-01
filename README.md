<h1>Bike Share Project</h1>


<h2>Project Description</h2>
The project involves a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The team aims to understand how casual riders and annual members use Cyclistic bikes differently to design a new marketing strategy to convert casual riders into annual members. The recommendations must be backed up with compelling data insights and professional data visualizations.
<br />

<h2>About the Company</h2>
Cyclistic launched a successful bike-share offering in 2016. The program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Moreno believes that maximizing the number of annual members will be key to future growth. Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members.
<br />

<h2>Programs and Languages Utilized</h2>

- <b>Excel</b> 
- <b>SQL</b> </b> <b><a href="https://docs.google.com/document/d/14r6P8wkU_-a02wb2xuPyjLq6n_H4Z1TJn_Jbe5ztmgw/edit?usp=sharing">link to scripts and analysis
- <b>Tableau</b>
- <b>Google Slides</b> <b><a href="https://docs.google.com/presentation/d/1lKEfvHA1A0PwmzfiniiFrlW4KaJ01p5mnufWade_g_Y/edit?usp=sharing">link to presentation 


<h2>Analysis walk-through:</h2>
(Cyclistic is a fictional company and the data has been made available by Motivate International Inc. under this <b><a href="https://ride.divvybikes.com/data-license-agreement"> license</b>.)

<br /> <br /> </b>

I secured the original data by storing it in my password-protected Google Drive. I then made copies of all the files and added a suffix of ‘…v1’ to each one. I opened each file in Microsoft Excel to review the data and determine what type of information was available. During this process, I added several columns to the data:
<br /> <br />a. "ride_length" which is calculated by subtracting the "started_at" column from the "ended_at" column (=D2-C2). 
 <br /> <br /> b. "day_of_week" which is calculated by using the "WEEKDAY" command (=WEEKDAY(C2,1))
These formulas were copied down to include all rows of data for each spreadsheet. 
<br /> <br />

After transferring the data to SQL, I conducted a thorough analysis and extracted valuable insights on emerging trends. To see a detailed walkthrough for SQL along with the scripts, follow this link.

![image](https://user-images.githubusercontent.com/129348678/229315371-b4d2670c-c8df-459b-b50f-7053295820ad.png)


<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
