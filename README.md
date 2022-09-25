# Pewlett-Hackard-Analysis

Overview of the analysis

This analysis is designed to guide Pewlett-Hackard company on their employees retirement schedules and training process for new recruitment. 

Results
1. The Retiremnt Title table shows all employees titles who were born between January 1, 1952 and December 31, 1955. It holds a total of 133776 records due to duplicate entries for employees who had occupied or switched various titles. 

![retirement_titles](https://user-images.githubusercontent.com/109990578/192123250-f505ef0c-ce49-4df5-ac59-9ab8f4c6d59f.png)

2. The Most Recent Title table was created using `DISTINCT ON` syntax  and has a record of 72458 employees and their titles.

![unique_titles_current](https://user-images.githubusercontent.com/109990578/192123557-495bc28c-3b30-4871-8131-f460521022e7.png)

3. The Retiring Titles table was created using `ORDER BY COUNT()` function for most recent job title who are about to retire.

![retiring_titles](https://user-images.githubusercontent.com/109990578/192123672-c443a72d-a268-4744-9002-524fdb183f49.png)

4. The Mentorship Elegibility table holds 1549 records of employees who are eligible to participate in a mentorship program.

![mentorship_eligibilty](https://user-images.githubusercontent.com/109990578/192123707-d1d701bd-e24d-49f0-8faf-7b446ce159d7.png)

Summay
