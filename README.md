# PowerBI-HR_Dashboard

This is a guided project to learn Power BI by codebasics on YouTube (www.youtube.com/watch?v=JC66t9eM10s)

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMWU0YmM4YjUtNTY4OC00MGI5LWIzMGYtZDk0ZmNkNWFhNDBkIiwidCI6IjhhOGY0OGUyLTdmOTktNDU5OC05MTAwLWEwZjBjY2M0Yjg5NiIsImMiOjZ9

## Objective

The dashboard provides insights into employee preferences for working from home versus working from the office over time, as well as employee wellness trends. It allows employers to identify patterns when multiple employees take sick leave during specific months, enabling proactive measures. Additionally, it assists in understanding why employees frequently choose to work from home on certain days of the week. This information can be used to schedule in-person team-building activities or meetings on days when employee attendance is highest. Moreover, in a hybrid work model, the dashboard supports data-driven decisions for optimizing office capacity planning when concerning space utilization and infrastructure costs.

### Steps followed 

- Step 1 : Load and transform Excel data by merging multiple sheets with different column headers (representing dates) into a single column. Ensure the process avoids hard coding, allowing it to be applicable to additional sheets.
- Step 2 : Add extra columns (work from home count, month, sick leave count, day of week) to the transformed data, alongside measures using DAX (present %, present days, sick leave %, sick leave count, total working days, work from home %, work from home count). The measures are organized together in a separate measures table.
- Step 3 : Display presence %, work from home %, and sick leave % on the dashboard, segmented by employee, day of the week, and overall trend by date. Additionally, break down the data by each month.

## Insights

A single page report was created on Power BI Desktop and it was then published to Power BI Service provided in the above link. 

### Apr 2022 - Jun 2022

#### Presence
- 91.83%
- Decreasing trend
- Most present on Monday and least present on Friday

#### Work From Home
- 10.00%
- Trending with little variation
- Work from home highest on Friday and lowest on Tuesday

#### Sick Leave
- 1.10%
- Increasing trend
- Highest sick leave on Monday and lowest on Friday






