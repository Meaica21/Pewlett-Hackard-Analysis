# Pewlett-Hackard-Analysis

## 1.	Overview of the analysis: 

The purpose of this analysis is to provide the total number of retiring employees per title and to check all eligible employees for mentorship program based on the hire date.

## 2.	Results: 

-	 The first major point is using INTO for creating new table in the database as shown on figure 1.

![Figure 1](https://user-images.githubusercontent.com/83877498/124401462-bc5a4f00-dcf7-11eb-8537-24da7c5a57e8.PNG)

Figure 1: Script for creating new table using INTO syntax

- Second major point is connecting two tables using JOIN on the primary key as well as utilizing aliases for table names.

![Figure 2](https://user-images.githubusercontent.com/83877498/124401509-e1e75880-dcf7-11eb-96fb-4492ba562893.PNG)

Figure 2: Using JOIN and Aliases 

-	The third major points is using an aggregate functions like COUNT with ORDER BY or GROUP BY statement.

![Figure 3](https://user-images.githubusercontent.com/83877498/124401525-f75c8280-dcf7-11eb-9e9e-6cd2702f7c57.PNG)

Figure 3: Aggregate functions

-	And the last major point I noticed was DISTINCT ON clause to remove the duplicate records in the result.

![Figure 4](https://user-images.githubusercontent.com/83877498/124401622-591cec80-dcf8-11eb-88d9-acd279b538bc.png)

Figure 4: Using DISTINCT Clause

o	How many roles will need to be filled as the "silver tsunami" begins to make an impact?  90,398 employees will be needed to fill 7 roles.

![Figure 5](https://user-images.githubusercontent.com/83877498/124401633-705bda00-dcf8-11eb-8d37-3fca45b5aa49.PNG)

Figure 5: Total Retiring Employees

![Figure 6](https://user-images.githubusercontent.com/83877498/124401646-8073b980-dcf8-11eb-8ad8-393ebaf6874f.PNG)

Figure 6: Seven Roles

o	Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?  No, they only have 1,549 employees eligible to participate in the mentorship program.  In that case, it will be difficult to replace retiring employees.  As of right now, each mentor-eligible employee will need to train 58.4 employees.  Therefore, Pewlett Hackard should try to train using online modules and classes

![Figure 7](https://user-images.githubusercontent.com/83877498/124401657-971a1080-dcf8-11eb-9077-212b9ed88477.PNG)

Figure 7: Total count for Mentorship eligibility







