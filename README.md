# Overview of Pewlett-Hackard-Analysis

The purpose of the analysis is to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. 

To determine the number of retiring employees per title the following queries were created: 
1. Retrive employees names, titles and filter by birth date (January 1, 1952 and December 31, 1955)
2. Filter by current employees 
3. Remove duplicate rows for employees with multiple titles throughout their carrer and only retrive their most recent title 

To identify employees who are eligible to participate in a mentorship program the following query was created
1. Group current employees that were born between January 1, 1965 and December 31, 1965 

# Results

A total of 72,458 employees are elegible for retirement and the breakdown by title can be found on the image below: 
- 36% of the positions are Senior Engineers and 34% are Senior Staff
- The remaining 30% is for Engineers, Staff, Technique Leaders, Assistant Engineers and Managers
- Only 2 managers will be retiring soon 

<img width="285" alt="Screen Shot 2022-06-15 at 2 45 27 PM" src="https://user-images.githubusercontent.com/104380112/173908132-d3ead5f0-fcef-4be9-b86b-ac5e943cd79d.png">

A total of 1,549 employees are elegible to participate in a mentorship program to train new associates. The table below includes their name and their current position: 

![Screen Shot 2022-06-15 at 4 27 27 PM](https://user-images.githubusercontent.com/104380112/173920939-75a45568-efee-4fcb-bffb-a68b79ea957a.png)

# Summary

How many roles will need to be filled as the "silver tsunami" begins to make an impact?
72,458 employees are elegible for retirement, however HR can include additional information by categorizing retirees into years, departments and titles. This information can answer when are they going to retire, which department are they in and the position that needs to be filled. 

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Using our query above there is not enough employees ready to mentor new associates. However, to increase the number of employees HR can expand the birth_date filter to include younger employees and not just those born in 1965. 
Also it would be helpful to categorize elegible employees by year, department and title to determine when employees are expected to be eligible for the mentorship program, their department of expertise as well as the titles they have had throughout their career 
