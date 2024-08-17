# PWC-CALL-CENTER
Created a power bi dashboard analysing the productivity of the call center department
created measures like counting number of row
Answered Calls = CALCULATE(COUNT(Sheet1[Call Id]),FILTER(Sheet1,Sheet1[Answered (Y/N)]="Y"))
Calls Not Answered = CALCULATE(COUNT(Sheet1[Call Id]),FILTER(Sheet1,Sheet1[Answered (Y/N)]="N"))
Not Resolved = CALCULATE(COUNT(Sheet1[Topic]),FILTER(Sheet1,Sheet1[Resolved]="N"))
Resolved Calls = CALCULATE(COUNT(Sheet1[Call Id]),FILTER(Sheet1,Sheet1[Resolved]="Y"))
Total = COUNT(Sheet1[Call Id])
number of topics = DISTINCTCOUNT(Sheet1[Topic])
weekdays
weekends
inserting images
and giving insights
