# Online Food Ordering System Database Design and Management

The **main objective** of this project is to **design** and **manage the database** at both **administration** and **user levels**. In addition, developed the **Data Visualization** by creating different **plots of tabular data** to help in **analyzing and generate useful insights**. 

**ER Diagram** is used to represent the **logical model** of database with **entities and attributes, relationships, unique identifiers and cardinality ratio** between entities. 

<details>
<summary>The Entity Relationship Diagram</summary>
  
![updated_food_order](https://user-images.githubusercontent.com/35762778/165653104-0ac84a25-97dd-4dbd-a9e1-6744e2367c2e.png)
</details>

<details>
<summary>Documentation of Database design and management</summary>
  
  [Document](https://github.com/Nisarg2612/MySQL-Project/blob/main/CS540_Online_Food_Order_Project.pdf)
</details>

<details>
<summary>Project Presentation</summary>
  
  [Google Slides Presentation](https://github.com/Nisarg2612/MySQL-Project/blob/main/CS_540_Online_Food_Order_Project.pdf)
</details>

---
### Database Administration Commands

**Connect to the MySQL server**
```
mysql -u root -p
```

**Create a database**
```
CREATE DATABASE database_name;
```

**Create a new user**
```
create user 'jenish' indentified by 'password';
```
![image](https://user-images.githubusercontent.com/35762778/165655429-41223b6f-4ee8-4537-bd77-6d67fbb42e68.png)

**Check the default privileges of user**
```
show grants for 'user_name';
```
![image](https://user-images.githubusercontent.com/35762778/165655537-ad1b6635-7e21-47ca-99d5-35111a679993.png)

**Create a tablespace in the database**
```
CREATE TABLESPACE tablespace_name add datafile 'datafile_name.ibd';
```
![image](https://user-images.githubusercontent.com/35762778/165655623-f081e7ec-c8da-4602-90d9-3c768a6974d1.png)
![image](https://user-images.githubusercontent.com/35762778/165655628-ce450ab1-9e26-4cd3-a6fc-9cb19f230d4d.png)

**To get the user list of MySQL local instance**
```
select user from mysql.user
```
![image](https://user-images.githubusercontent.com/35762778/165655692-787a6d71-fd21-4246-ba41-b48105af88b5.png)

