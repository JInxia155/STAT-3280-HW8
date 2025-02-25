Download Link : https://programming.engineering/product/stat-3280-hw8/

# STAT-3280-HW8
STAT 3280 HW8
Total points: 10.

    [2 pts] Determine the best data type to use for each example below, e.g., state abbreviation = fixed-length character, char. If a number note as unsigned if appropriate.

        An article from the New Yorker Magazine

        Time of a runner finishing a multiday competition

        Time elapsed between births of twins

        Car Make

        Date and time of homework submission

        Longest throw from a Quaterback in feet

        Whether someone likes beer or not

        UVA id number (not computing id)

    [2 pts] Based on the provided department table below, provide the SQL code to create a SQL table called employees that stores employee number (primary key), employee name, department, and salary information. Have the foreign key on the employees table reference the departments table based on the department_id field.

CREATE TABLE departments ( department_id INT,

department_name VARCHAR(50),

CONSTRAINT departments_pk PRIMARY KEY (department_id)

);

The following questions are based on the suppliers table shown below:
	

supplier_id
	

supplier_name
	

city
	

state

100
	

Microsoft
	

Redmond
	

Washington

200
	

Google
	

Mountain View
	

California

300
	

Oracle
	

Redwood City
	

California

400
	

Kimberly-Clark
	

Irving
	

Texas

500
	

Tyson Foods
	

Springdale
	

Arkansas

    [2 pts] Provide the SQL code to create and fill in the table suppliers shown above.

    [2 pts] Provide the SQL code to update the city to ‘Boise’ and the state to ‘Idaho’ for all records whose supplier_name are ‘Microsoft’.

    [2 pts] Based on the suppliers table, provide the SQL code to delete the supplier record whose state is ‘California’.
