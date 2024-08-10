# HR-Dashboard

This is a guided project to learn Power BI by codebasics on YouTube (www.youtube.com/watch?v=JC66t9eM10s)

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMWU0YmM4YjUtNTY4OC00MGI5LWIzMGYtZDk0ZmNkNWFhNDBkIiwidCI6IjhhOGY0OGUyLTdmOTktNDU5OC05MTAwLWEwZjBjY2M0Yjg5NiIsImMiOjZ9

## Problem Statement

The dashboard helps in understanding employee 


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Gate Location" & "Type of travel".
- Step 9 : Two card visuals were added to the canvas, one representing average departure delay in minutes & other representing average arrival delay in minutes.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
