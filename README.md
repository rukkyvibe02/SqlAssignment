# Database Assignment

### Application Downloaded
- PostgreSQL-16.0-1-windows-x64

### Application Used
- PgAdmin 4

### Assignment
- Create a database called (sport) having a table with the name nba using the above CSV.

[website](https://youtube.com)

## Steps
### Step 1
Create a database called ( sport) having a table with the name nba using the above csv.
First step in creating a database
- *Open your PgAdmin
![1 - PgAdmin 4 interface](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/252920c8-90e0-433b-b81e-d07177502188)

### Step 2
![2 - Select Sql from the Tabs](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/40815310-77eb-4e8b-82eb-2910131b9a01)
 Select SQL from the Tabs

 ### Step 3
 ![3 - creating ur database name](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/a6b1c84e-d79d-4202-8ff0-487bc0afafdc)
creating ur database name
- •	Select server
- •	Select PostgreSQL
- •	Select Database
- •	Select postgre
- •	Schemas
- •	Right-click on Schema and select Query tool. And u will get this page above.

![4 - creating your database name](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/d7f1b59e-8b59-43c3-b79d-f1715e7a7dbe)
- •	Now to create the database youu have to type this command >> create database sport;
- •	Then you click on the play sign to run.

![5 - Refresh database to see the new database created](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/887bdc82-76da-4d03-a598-2bdfe09466ad)
- refresh the Database to see the new database created

![6 - accessing the new database table](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/4b35b510-ac37-4d12-a0ab-91b377294f24)
- accessing the new database table
- * Refresh the Database to see the new database created
- * you click on it.

![7 -  table successfully created](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/01d3e3df-a217-4172-a910-23a47b49d428)
- Right-click on the database name and select Query tool to create a table in the new database you created.
- With these command table has been created successfully in the database
- create table movies (
-    Name VARCHAR(64),
-  	Team VARCHAR(150),
-  	Position VARCHAR(64),
-  	Birthday VARCHAR(64),
-  	Salary VARCHAR(50)	
-  	);


![8- inserting values in the table](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/9c24b576-00a7-492e-a6a0-552f85dddb2f)
- To insert values into the table use the following command:
- INSERT INTO nba (Name,Team,Position,Birthday,Salary) values('Shake Milton','Philadelphia 76ers','SG','1996-09-26','1445697');
- Before you run this command make sure you comment on the command you used in creating the table by adding a double (- -) without space.

![image](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/a74c097f-d240-4b3c-a1e8-99e3ab0ddcfd)
-Uses this command to view the values you typed on the table:
select * from nba;

![9 - adding another value to the table](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/ce431d3d-26e2-4463-b9a8-046d44aaf61a)
- Adding another values to the table with the previous process comment and use this command to view >> select * from nba;
- -- INSERT INTO nba (Name,Team,Position,Birthday,Salary) values('Christian Wood','Detroit Pistons','PF','1995-09-27','1645357');

![9 - viewing the values you insrted](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/e6e2c407-d076-4447-8c44-6404b0d8c685)
- viewing the values you insrted

![10- removing values](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/d55dbe65-88b1-449f-a54d-c8bc8cf03919)

## Next step is to (delete) drop all the values we have inserted on the table and insert a csv file to the database we have created, using this command: DROP TABLE nba;
![10- removing values](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/29ac055a-9bae-490e-b9b8-3d5be15a789a)
- Values successfully removed.
- After removing all make sure you uncomment on the create table and from name to salary and run to enable you import the csv file successfully.

![11 - importing](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/2f7f10f6-f1d7-40cd-9c3d-b89543009d15)
- Now refresh the table nba and right click again and click on import , locate  your csv file and import

![12 - select file name](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/2fe7018a-bf1c-49c9-907d-fedf0aa8cdff)
- Importing interface, select file name to locate the file 

![13 - file located](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/5e2e7982-dbe6-4f49-b82b-7be2051c67fd)
- File located

![14 - file imported successfully](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/0292e6df-57e4-4d54-9820-82ec2e49a3e1)
- My csv nba file has been imported successfully as you can see.
- To view the content of the file type this command >> select * from nba;

![15 - view imported file successfully](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/645a250d-b815-470f-8bcd-a57457b13ce7)
- Content of the file viewed successfully with the command >> select * from nba;

![16 - counting the number of rows](https://github.com/rukkyvibe02/SqlAssignment/assets/146957698/36dde8ab-2a9a-4d21-ad5d-04ab588b46ce)
- Finally, you use this command to count the total number of rows in your imported csv file >> select count(*) from nba;
From this file, we have a total of 451 rows.

- The End!!!
















