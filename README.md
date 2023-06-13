<h1>SQL Skype Exercise</h1>


<h2>Description</h2>
On Hue worked with SQL to practice with two CSV files containing mock Skype info.
<br />


<h2>Methods Used</h2>

- <b>WHERE</b>
- <b>ORDER BY</b> 
- <b>GROUP BY</b> 
- <b>JOIN</b> 
- <b>DISTINCT</b> 
- <b>LIMIT</b>
- <b>AVG</b>
- <b>COUNT</b> 

<h2>Materials Used </h2>

- <b>Hue</b>
- <b>SQL</b>
- <b>CSV file</b>

<h2>Project walk-through:</h2>

<p align="center">
Show the data structures and the first 10 records of each table. Use a SELECT query to show the records: <br/>
<img src="https://imgur.com/M9n9w0F.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
How many females older than 25 found Skype to be easy to use (i.e., EasyToUse >= 4):  <br/>
<img src="https://imgur.com/SzwRLZx.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Show UID, Gender, Age, EasyToUse and FutureUse of the US users who spent more time in each session of Skype (i.e., UseDuration = 1 to 3 hours and UseDuration = 30 – 60 minutes):  <br/>
<img src="https://imgur.com/qPyoFrL.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Show the average FutureUse by country and sort the results by country:  <br/>
<img src="https://imgur.com/gveyjqp.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Implementing a query to show whether there is a gender difference in UseDuration:  <br/>
<img src="https://imgur.com/hxkFiTv.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<p align="left">
<br />
The last question gave me more freedom to come up with an answer. It was more open-ended and for this question I decided to group and order by gender while counting the total. I also had to join the two csv files to make it work. The result was a nice, clean and easy to interpret answer.
<br />
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
