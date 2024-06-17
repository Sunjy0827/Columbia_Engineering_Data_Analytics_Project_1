# Columbia_Engineering_Data_Analytics_Project_1

# PROJECT I

###### - Team Members: Karen Lin, Kevin Zhang, Sunjae Youm </br> - Date: 6/17/2024 </br> - Data Source: https://catalog.data.gov/dataset/crash-reporting-drivers-data/resource/9851a37f-4f32-464e-8ba6-c23023653a7f

### **Abstract**
<p>
Our data team assumed that we received a request from the Montgomery County local government in Maryland. The purpose of the request was to determine how to use the county budget to improve traffic and reduce car accidents. Additionally, Montgomery County wanted to choose a specific municipality and asked us, as data analysts, to identify which roads need immediate improvements. To achieve this, we investigated traffic accident records from January 2015 to March 2024, analyzing the areas with the highest number of accidents , the time periods with the most accidents, and whether there were traffic control regulations in place at the accident locations.
</p>

### **Data Processing**
<p>
<ol>
<li>Loaded all dependencies/libraries for the data processing</li>
<li>Loaded raw_data_file after downloading it and filtered out the rows have no values in the Municipality column </li>
<li>Reformat the DataFrame with only the required columns after exploring the data using a pivot table in Excel. </li>
<li>break out the column "Crash Date/Time" to "Date", "Time", "Year", "Month", "Day" for detail analysis - Used CHATGPT </li>
</ol>


### **Chart and Visualization**
<ol>
<li>created a pie chart to narrow down which municipality has the most car accidents</li>
<li>narrowed down to "ROCKVILLE" Manucipality and looking at the # of car accidents between 2021 and 2023</li>
<li>Draw a map plot to visually show which road has the most accidents </li>
<li>In order to clarify the road, grouped the data by "Road Name" and plot the horizontal bar graph</li>
<li>focused on the Road Name Rockville Pike and start lookin at the number of accidents by three angles "Speed Limit", "Traffic Control", "Surface Condition"</li>
<li>Broke down the number of car accidents by hourly intervals and create the frequency table and histogram - Used CHATGPT to create the hourly intervals</li>
<li>group by Year-month to see the trend of car accidents in three years (2021-2023)</li>
</ol>

### **Analysis**
<ol type="I">
<li>From the grouped_df1 and the pie chart representing the top 5 municipalities showing the number of car accidents, the 'ROCKVILLE' municipality has the highest number of car accidents.<br><b>`image_1` & `image_2`</b></li><br>
<li>From the f1_grouped_df1 and the horizontal bar chart representing the top 10 Roads, the 'ROCKVILLE PIKE' Road has the highest number of car accidents. <br><b>`image_1` & `image_2`</b></li><br>
<li>
Draw a map plot to visually show which road has the most accidents
<br><b>`image_1` & `image_2`</b>
</li><br>
<li>filtering the dataset by Road Name 'ROCKVILLE PIKE'
<ol type="i"><br>

<li>
The number of car accidents on ROCKVILLE PIKE from the perspective of <b>Speed Limits.</b> 80% of the number of accidents were occured between 35 and 45 limit.
<br><b>`image_1` & `image_2`</b>
</li>

<li>
The number of car accidents on ROCKVILLE PIKE from the perspective of <b>Traffic Control</b>. Car accident near Traffic Signal was the number one reason among other traffic controls
<br><b>`image_1` & `image_2`</b>
</li>

<li>
The number of car accidents on ROCKVILLE PIKE from the perspective of <b>Surface Condition</b>.<br> There was any significant relationship between surface condition and number of car accidents
<br><b>`image_1` & `image_2`</b>
</li>
</ol>
</li><br>
<li>Number of car accidents by Hourly Intervals<br>
The number of car accidents were higher than other hour interval at between "12:00 PM and 1:00PM", "02:00PM and "06:00PM" and "07:00 PM and 08:00PM".
<br><b>`image_1` & `image_2`</b>
</li><br>
<li>number of car accidents by Year-Month<br>There is a pattern observed that car accidents increase in June every year
<br><b>`image_1` & `image_2`</b></li>
</ol>

### **Conclusion**
<ol>
<li> Reducing the speed limits on the zone have 35 & 40 speed limit would help reducing the car accidents numbers</li>
<li>The road has higher speed limit and normally drivers get into the car accident when they try to pass the yellow light. With that said, shorting the yellow light time would help improve the number of car accident</li>
<li>Place more traffic polices on the ROCKVILLE PIKE on that time intervals</li>
<li>"Karen's Part"</li>
</ol>

</p>