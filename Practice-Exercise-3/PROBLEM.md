**SystemAdmin-1: Creating and Managing Users and Groups**

**Important Note:**

1) Document the sequence of commands you are executing in order to perform the update in solution.md in the exercise folder​

2) Submit document file once you achieve his goal.​

3) You have to use Ubuntu 18.04 vagrant file for virtual machine in exercise-3.
​

**Practice Exercise 3: Group Permission**
​

Exercise 3: Problem Statement

John, from the Sales Department, wishes to access the DATA directory of the Account’s Department. The department has strict instructions not to allow John to use this folder. ​

Ensure that John is not able to access the DATA directory while enabling access to users in the Accounting department.
Create a DATA directory.​

Create three files in the directory: Customer.txt, Accounting.txt, and Sales.txt ​

Create users Brian and Smith. They work in the Accounting department and require access to the directory. ​

Set permissions on the DATA directory as:​

Owner: root : rwx​

Group: account: rwx​

Other: - - -​

Ensure that user John, who is part of the Sales department, is not able to access the DATA directory. ​

Note: Create users and groups and set permissions accordingly.​
​
​
