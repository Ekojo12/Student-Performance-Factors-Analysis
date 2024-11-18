# Student-Performance-Factors-Analysis
A group project on Education Data Analysis, Student Performance Factors

## Outline
## [Project Overview](#project-overview)
## [Data Sources](#data-sources)
## [Tools Used](#tools-used)
## [Data Analysis](#data-analysis)
## [Insights](#insights)


### Project Overview
---
This is a group project assigned during learning at SkilHarvest Data Analysis Program.
Group 5

1. Download a dataset
   
2. Create visual from a dataset

3. Document your step by step analysis from the Data given.

4. Tell a story about the visuals

### Data Sources
---
The data used for this assignment was downloaded from.
Dataset has 10 columns and 30,800 rows

### Tools Used
---
- MS Excel [Download Here](https://www.microsoft.com)
    1. This is the major tool used for analysis and visualization

### Data Analysis
---
Additional Columns were added using Excel functions;
Exam Score Remarks
```
=@IFS(G3<=50,"Fair",G3<=65,"Good",G3<=80,"Very Good",G3>80,"Excellent")
```
Average Daily Study Hours
```
=A2/7
```
Attendance Impact
```
=G2*(B2/100)
```
Distance from Home
```
=@IFS(T2<=6,"Far",T2<=10,"Moderate",T2>10,"Near")
```

### Insights
---
This has been documented in the Report Uploaded.

