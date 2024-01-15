
 # H1B Visa Analysis PowerBi Project-

### Dashboard Link : https://app.powerbi.com/Redirect?action=OpenReport&appId=506e5b07-81d0-4b7a-af7e-2370a83940dd&reportObjectId=f3f6b0a4-4c3a-4037-87e5-b2a84af98601&ctid=c3e8fb7a-11a9-4a44-a1b4-1dda7786becf&reportPage=ReportSection50b9fc72437b15e7280b&pbi_source=appShareLink&portalSessionId=69d73da8-7463-4307-93e2-7f8723aa306c

## Problem Statement

This dashboard helps the Visa appliactions understand their customers better. It helps to know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the average delay of application, thus since by using this dashboard they have identified this problem.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened, so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 7 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Location".
           
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.

- Step 8 : A bar chart was also added to the report design area representing the number of satisfied & neutral/unsatisfied customers. 
- Step 9 : Pie chart Visual was used to represent different ratings mentioned below,

- Step 10 : Analysis
  
- Top 10 Hiring Companies:
This report highlights the ten companies that have the highest number of successful hires through visa petitions. It provides insights into the industries and sectors where these companies are actively recruiting foreign workers.

- Average Prevailing Wage by Employer:
This analysis presents the average prevailing wages offered by different employers in visa petitions. It helps in understanding the salary trends across various companies and industries for foreign workers.

- Top 10 States with Highest Application Counts:
This report identifies and ranks the states with the highest number of visa applications. It sheds light on the geographic distribution of visa petitions, indicating regions with high demand for foreign workers.

- Distribution of Applications by Job Titles:
This analysis categorizes and illustrates the distribution of visa applications based on job titles. It provides insights into the specific roles that are in demand among employers seeking foreign talent.

- Top 10 States with Highest Denied Petitions:
This report outlines the states with the highest number of denied visa petitions. It helps in understanding the challenges or scrutiny faced by applicants in certain regions.

- Top 10 Job Titles with Highest Prevailing Wages:
This analysis identifies the job titles that offer the highest prevailing wages. It provides information on the types of roles that are associated with higher compensation for foreign workers.

- Occupation Analysis:
This report delves into the details of various occupations sought through visa petitions. It provides a breakdown of demand for different professions, offering insights into the industries driving foreign employment.

- Top 10 Worksite Locations:
This analysis highlights the specific worksite locations where foreign workers are most commonly placed. It offers information on the geographic distribution of job opportunities for visa holders.

- Map Visualization:
Using geographical data, this visualization tool maps out the distribution of visa applications, denials, or approvals. It provides a visual representation of the concentration of foreign employment activities.

- Case Status Distribution:
This report categorizes and illustrates the distribution of visa cases based on their status (approved, pending, denied). It helps in understanding the success rates and challenges associated with visa applications.

- Visa Application Trends Over the Years:
This analysis tracks the trends in visa applications over a specified period. It provides insights into the changes in demand for foreign workers and how it has evolved over time.

- Denied Petitions Over the Years:
This report examines the trends in denied visa petitions over a specified time frame. It helps in identifying patterns or factors contributing to an increase or decrease in petition denials.  
  
All these values have been ignored while calculating average rating for each of the parameters mentioned above.
         
 - Step 10 : The report was then published to Power BI Service.
 
![image](https://github.com/Manjesh30Verma/H1B_PowerBi/assets/144987266/955fc926-d378-4b77-a84a-4483cec92bc1)

![image](https://github.com/Manjesh30Verma/H1B_PowerBi/assets/144987266/d19e8ead-850b-4ff9-b515-8d19f8d7174b)


# Snapshot of Dashboard (Power BI Service)

![image](https://github.com/Manjesh30Verma/H1B_PowerBi/assets/144987266/de1a3d5b-745c-4a63-b52b-b2f6f54ce1e8)
