# Pewlett-Hackard-Analysis

## Overview

The purpose of this analysis is to help Bobby identify employees who are most likely to retire soon by their title and employees who could transition to a mentorship program.

## Results

1. After creating the first query to get the retirement list by titles, the query resulted in many duplicates due having multiple positions.
![RetirementTitles](/Images/retirement_titles.png)
2. Using 'DISTINCT ON' removed the duplicates, leaving the most recent job title to create a unique and clean list of retiring employees.
![UniqueTitles](/Images/unique_titles.png)
3. The Retiring by Title count total is 90,398 potentially retirees.
![RetirementTitles](/Images/retiring_titles.png)
4. 1549 employees born in 1965 are eligible for a mentorship opportunity.
![Mentorship](/Images/mentorship_eligibility.png)

## Summary

