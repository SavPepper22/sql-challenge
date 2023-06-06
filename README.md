# sql-challenge
Hello this is my submission for the Module 9 challenge. 
The background for the assignment is that I am a new hired data engineer at Pewlett Hackard (a fictional company). My first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.
The csv files where labelled as departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, and titles.csv.
First I had to import the CSV files into a SQL database, and then answer questions about the data.
So I perform data modeling, data engineering, and data analysis, respectively. 

## More Information
### Data Modeling

I inspected the CSV files, and then sketch an Entity Relationship Diagram of the tables. To create the sketch I used QuickDBDLinks to an external site. I took a screenshot and saved it as a png file named ERD Diagram.png.

### Data Engineering

+ Using the provided information to create a table schema for each of the six CSV files. I did the following:
+ Specify the data types, primary keys, foreign keys, and other constraints.
+ For the primary keys, verify that the column is unique. Otherwise, create a composite keyLinks to an external site., which takes two primary keys to uniquely identify a row.
+ Then create the tables in the correct order to handle the foreign keys.
+ And then finally import each CSV file into its corresponding SQL table.

This information is saved on the Schema.sql file.

### Data Analysis

After looking over all the tables that had been imported and making sure they worked correctly I then began answering questions for the analyis using the pgadmin. I answered the following question:

1. List the employee number, last name, first name, sex, and salary of each employee.
2. List the first name, last name, and hire date for the employees who were hired in 1986.
3. List the manager of each department along with their department number, department name, employee number, last name, and first name.
4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
6. List each employee in the Sales department, including their employee number, last name, and first name.
7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

I saved my work with the questions on the analysis.sql file.
