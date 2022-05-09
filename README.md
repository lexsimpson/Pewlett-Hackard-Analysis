# Pewlett-Hackard-Analysis
## Overview
The purpose of this assignment is to help a company named Pewlett-Hackard. They have several thousand employees, many of which are due for retirement soon. This company would like to get a list of all the retiring employees in order to build retirement packages for them, and also figure out which positions they will soon have to fill.
## Results
  * First, I created the retirement_titles table filtering by birth date in order to get the employees who may be eligible for retirement. However, there are duplicate entries for employees due to them switching titles over the years. This is the purpose for making the unique_titles table. In order to make this table I needed to filter the to_date column to make sure it was up to date.
  * Then, I created the retiring_titles table to show a count of each title that will be retiring soon. It looks like they will need to fill a lot of senior engineer positions soon.
  * Deliverable 2 was all about finding out if Pewlett-Hackard had the employees to mentor the new employees they would soon need to hire. In order to do this I needed to filter by the to_date in order to find current employees, and the birth_date to find employees retiring soon.
  * I did run into an error trying to filter these results. I was receiving a syntax error and could not figure out why so I reached out to the learning assistants, and it was just a simple mistake of adding an extra set of parenthesis. To correct this I added the code below and finally got the results I was expecting.
  
     ![Screen Shot 2022-05-08 at 4 29 13 PM](https://user-images.githubusercontent.com/98988407/167320984-1c39fb6f-fb66-4d48-bdb4-ff162e91c048.png)

## Summary
There are a total of 72,458 employees across various roles at Pewlett-Hackard that are soon to be retiring.
In order for Pewlett-Hackard to be prepared for the "silver tsunami" they will need to hire new employees to fill these roles quickly, so they can be trained by current employees and be fully competent in their roles by the time the retiring employees leave.
