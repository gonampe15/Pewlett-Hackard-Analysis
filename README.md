# Pewlett-Hackard-Analysis

## Overview

The purpose of this analysis is to help Bobby identify employees who are most likely to retire soon by their title and employees who could transition to a mentorship program.

## Results

1. After creating the first query to get the retirement list by titles, the query resulted in many duplicates due having multiple positions.
![RetirementTitles](/Images/retirement_titles.PNG)
2. Using 'DISTINCT ON' removed the duplicates, leaving the most recent job title to create a unique and clean list of retiring employees.
![UniqueTitles](/Images/unique_titles.PNG)
3. The Retiring by Title count total is 90,398 potentially retirees.

![RetirementTitles](/Images/retiring_titles.PNG)

4. 1549 employees born in 1965 are eligible for a mentorship opportunity.
![Mentorship](/Images/mentorship_eligibility.png)

## Summary

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?

We can see that potentially 90,398 roles will need to be back filled due to the "silver tsunami".

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

Using the criteria of those born in 1965, the potential mentee list is 1,549 employees. Comparing it to the number of future employees, it wouldn't be enough so management might want consider adjusting the year borned criteria.

Finally, give extra insight to both Bobby and management, two new tables were created.
- unique_mentors_list which provides a list of potential mentors filtered by birth date (about 35 years old) when starting a job and currently title.
- unique_mentor_count which provides a list of potential mentors by title counts.
