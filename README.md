# Student Marks Report Bot (UiPath RPA)

A UiPath automation that reads student marks from Excel, calculates each
student's Total and Average, and writes the results back to the same file.

## What it does
- Reads marks (Maths, Science, English, Computer) for 10 sample students
- Calculates Total and Average for each student
- Writes the updated table back to Excel with headers

## Tools used
UiPath Studio (Community Edition), Microsoft Excel

## How it works
Use Excel File > Read Range > Add Data Column (Total, Average) >
For Each Row in Data Table > Write DataTable to Excel

## Screenshots
See Workflow.png and Result.png

## Note
All student names and marks are sample data.