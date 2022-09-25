# Pewlett-Hackard-Analysis

## Overview of the analysis

This analysis is designed to guide Pewlett-Hackard company on their employee’s retirement schedules and training process for new recruitment by determining the number of retiring employees per title and identifying employees who are eligible to participate in a mentorship program for new interns.

## Results

1. The Retirement Title table shows all employee’s titles who were born between January 1, 1952, and December 31, 1955. It holds a total of 133776 records due to duplicate entries for employees who had occupied or switched various titles.

![retirement_titles](https://user-images.githubusercontent.com/109990578/192123250-f505ef0c-ce49-4df5-ac59-9ab8f4c6d59f.png)

2. The Most Recent Title table was created using `DISTINCT ON` syntax and has a record of 72458 employees and their titles.

![unique_titles_current](https://user-images.githubusercontent.com/109990578/192123557-495bc28c-3b30-4871-8131-f460521022e7.png)

3.The Retiring Titles table was created using `ORDER BY COUNT()` function for the most recent job title who are about to retire.

![retiring_titles](https://user-images.githubusercontent.com/109990578/192123672-c443a72d-a268-4744-9002-524fdb183f49.png)

4. The Mentorship Eligibility table holds 1549 records of employees who are eligible to participate in a mentorship program.

![mentorship_eligibilty](https://user-images.githubusercontent.com/109990578/192123707-d1d701bd-e24d-49f0-8faf-7b446ce159d7.png)

## Summay

With our findings we are able to answer the following;

- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
 Total of **72458** vacancies to be open soon.
 
- The findings show that 72458 vacancies will be available soon while 1549 current employees would be eligible for mentorship roles. The statistics between these numbers shows that each mentor will handle at least 46 interns which is too much for one person. So, there are not enough qualified, retirement-ready employees for mentoring the new interns.

### Additional queries or tables that may provide more insight into the upcoming "silver tsunami."

1. Mentors per job title table gives an insight on how many interns for each mentors.

![mentorship_per_title](https://user-images.githubusercontent.com/109990578/192124550-2364b1fc-76aa-43d0-a641-3fceaddc7549.png)

2. We can refactor the code to choose mentors born in 1952 as they are the first to be retired. This shows that 18537 records of potential mentors.
3. 
![mentorship_1955](https://user-images.githubusercontent.com/109990578/192124629-534ab447-1a5c-407b-9d24-54bef1b886c0.png)
