# Pewlett Hackard Analysis

## Overview of Project

Pewlett Hackard is a large company looking to appropriately prepare for the upcoming retirement wave of its Baby Boomer employees. 

1. PH would like to offer a retirement package to certain eligible employees.
2. PH would like to establish a mentorship program to train employees filling the expected vacant positions.

Provided with the following data:

![EmployeeDB](https://github.com/cewarkentin/Pewlett-Hackard-Analysis/blob/main/EmployeeDB.png)

we established a PH employee database and used SQL to make queries identifying the number of retiring employees by job title, as well as the employees eligible for the mentorship program.

Based on provided information, potentially retiring employees were identified based on birthdates between 1952-1955.

## Results

- The position potentially losing the most employees is a Senior Engineer (25,916 employees). Additionally, the position of Engineer is potentially losing the third largest amount of employees(9,285 employees). There is an additional potential 1,090 Assitant Engineer employees retiring. This leaves a total of 36,291 potentially vacant engineering positions.
- The position potentially losing the second most employees is a Senior Staff member, and the position of Staff is potentially losing the fourth largest amount of employees.
- The Mentorship Eligibility table only contains 1,550 employees based on the criteria used (a birthdate in 1965).
- Numbers across the various tables do not add up consistently. However, in Module 7.3.5 there were other odd observations leading to the following three questions: "What's going on with the salaries?", "Why are there only five active managers for nine departments?" and "Why are some employees appearing twice?" The data does not seem to be very clean.

## Summary

According to the retirement_by_department (Module 7.3.4), there are 36,619 potential future vacant positions. According to the retiring_titles table, there are a total of 72,458 potential future vacant positions.

- The Mentorship Eligibility table contains 1,550 employees so there are more than enough potential retiring employees to mentor 1,550 employees staying in the company.

I do not like the eligibility for the mentorship program being based on employee age-- I would prefer to look at length of employment as a measure of whether or not an employee should be eligible for mentorship and moving upward in the company. Or if there was data on employee performance. 
