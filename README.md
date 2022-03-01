# Overview of the analysis:
The following is a summary of our analysis of Pewlett Hackard’s HR review of potential retirees over the next few years and addresses the following deliverables: 
1.	Determine the number of retiring employees per title 
2.	Identify employees who are eligible to participate in a mentorship program
3.	Write a report that summarizes our analysis and helps prepare our manager for the “silver tsunami”, as many current employees reach retirement age.
## Results: There is a bulleted list with four major points from the two analysis deliverables. (6 pt)
•	There are 90,398 employees scheduled to retire over the next few years.
•	Of those destined for the ‘silver tsunami’ (aka retirement), as shown in ‘unique_titles.csv’, there are 25,916 Sr. Engineers, 24,926 Sr. Staff, 9,285 Engineers, 7,636 Staff, 3,603 Technique Leaders, 1,090 Asst. Engineers, and 2 Managers.
 
![retiring_titles](https://user-images.githubusercontent.com/96449605/156074366-e016c561-742f-4343-84bd-be7a3b4686e1.png)

•	After writing a query and creating a file for those eligible to participate in the mentorship program: there are 1,549 employees eligible to participate. 
•	Of the 1,509 eligible employees participating in the mentorship program, there are 402 Engineers, 392 Sr. Staff, 332 Staff, 290 Sr. Engineers, 77 Technique Leaders, and 56 Asst. Engineers.

![Mentors](https://user-images.githubusercontent.com/96449605/156074416-a816277f-bae3-4947-9489-7fb795480e81.png)

### Summary: The summary addresses the two questions and contains two additional queries or tables that may provide more insight. (5 pt)
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Ideally there would be 72,458 roles (overall) ready to be filled as replacement for those entering the “silver tsunami”. That’s a hefty number for any HR department. 
![Employees Leaving by Dept Code](https://user-images.githubusercontent.com/96449605/156256787-d382698a-7aa2-480c-9c78-a680df0923e

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
The short answer is no. Currently there are only 1,549 employees on the mentorship eligibility list. That’s roughly a 1:47 ratio of mentors to staff. Obviously not an ideal. This massive outflow of retiring employees and influx of new staff to replace them can be mitigated through a phased approach over the course of the next few years.
![Employees Leaving by Dept](https://user-images.githubusercontent.com/96449605/156256737-6a30a42c-f2ac-4b04-b7d7-1dcd5840533d.png)

In a nutshell, it all depends on how many retiring employees are willing to stay and mentor others. Regardless, a healthy mentor to mentee ratio would be around 1:3. That is one mentor for every three new employees. Assuming each year there are more or less 13,000 employees retiring and 13,000 new employees entering, we would need 3,000-4,000 mentors distributed proportionally through all the departments, however Development, Production, and Sales will be in need of the most attention…so the distribution isn’t entirely equitable. 

