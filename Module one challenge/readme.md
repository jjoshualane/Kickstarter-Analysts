
# Louise's Fundraising Data

## Summary:

### Louise contacted us about her fundraising goal for her play. She wanted us to gather data based upon launch dates and funding goals to see how they fared. She had a fundraising goal of ten thousand dollars for her play *Fever*. Louise's play came close to its goal in a short time and now she she wants a visualization of different campains so that she may have a more succesful fundraising in the future.


## Analysis

### I took the origanal kickstarter sheet and labeled it outcomes based on goals. I filtered and cleaned up the data. In a new sheet i created new columns of data for Louise's information she requested. I then gathered the goal,failed,canceled data. I then got the total number of projects. Afterwords i gathered the successful,failed,canceled percentages based on the function Year() in excel . Once all the data was collected i created a pivot chart for all the information gathered.

>The Year() function is used to return the year corresponding to a date.
>
>>{Microsoft}<https://support.microsoft.com/en-us/office/year-function-c64f017a-1354-490d-981f-578e8ec8d3b9>

Creating the Pivot Chart:

### The pivot table i created allowed me to use the data from the Kickstarter worksheet and put it into an easier format which allowed me to filter topics such as parent category and years involved. It would also allow me to display the amount that succeeded,failed, and canceled in their campaigns, and which month they occurred. I then filtered parent category for only theater and created a line chart to visually get a better understanding between the launch month and the outcomes.

#### Pivot Chart:
![Correct](https://user-images.githubusercontent.com/95378573/146635691-913e8a6b-5bb8-4451-a294-22a100145184.png)






#### Line Graph For Outcomes and Launch Months:


![Correct](https://user-images.githubusercontent.com/95378573/146635705-191ab5d8-1582-401f-8761-13a51a166445.png)

#### Creating Outcomes vs Goal Table:

After creating the pivot chart and line graph I wanted to break down the outcome based on goals. I created a table to help see the percentage of successful, failed, and canceled plays based on their funding goal. I started using the function countifs() to criteria ranges to count the successful, failed, and canceled campaigns within a five thousand dollar range.

>The COUNTIFS() function applies criteria to cells across multiple ranges and counts the number of times all criteria are met.
>
>>{Microsoft}<https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842>>

Data Table After Inputting Countifs() Formula:
![Screenshot 2021-12-18 042717](https://user-images.githubusercontent.com/95378573/146636337-e5d71e45-a5d0-4a75-82aa-9dfb42815494.png)

After getting all the data inserted correctly. I added cells successful, failed, and canceled togeather to get the total projects that met target. I then gathered the percentages of those categories. I then created a line graph to show the data and then filtered it to show percentages for every five thousand.

>The SUM() function adds values.
>
>>{Microsoft}<https://support.microsoft.com/en-us/office/sum-function-043e1c7d-7726-4e80-8f32-07b23e057f89>

>Finding percentage in excel you divide the part against the whole.
>
>>{Microsoft}<https://www.microsoft.com/en-us/microsoft-365/blog/2011/08/02/how-to-do-percentages-in-excel/>

#### Line Graph for Outcomes vs Goals:
![Screenshot 2021-12-18 042744](https://user-images.githubusercontent.com/95378573/146636902-45f1dade-5d5e-4973-9f27-4feb78a0c217.png)

## Results:

#### Theater Outcomes by Launch Date:
<ol>
  <li> The best time to launch a new campaign is in May.
</li> 
  <li> The worst time to launch a new campaign is in December.</li>
  </ol>

  #### Outcomes Based on Goals: 
  
<ol>
  <li>You will have the best success if you can keep you goal for a campaign under $15,000, although the most successful campaigns have been in the $1,000-$5,000 range.</li>
  </ol>
  
  #### Limitations:
  
  Some of the limitations of data were things such as reasoning behind the success, fail, or cancelation of the campaigns.There are many factors that play a role. Another is the amount of information, with more data we get more accuracy with our statistics. Also the age of the majority whats populare for the time period it all plays an important role in your success.
  
  
