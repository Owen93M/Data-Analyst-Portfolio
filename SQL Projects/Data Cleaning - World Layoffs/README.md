# World Layoffs - Data Cleaning Project

## Crating A New Schema
* Opening a **Schema** to house **Tables**.

<img width="1557" height="862" alt="1  New Schema" src="https://github.com/user-attachments/assets/c04450ee-07fa-49ae-8ca6-df69a3b3eef5" />

## Applying SQL Script
* Adding **SQL** to the database.
  
<img width="1407" height="771" alt="2  Apply SQL To Schema" src="https://github.com/user-attachments/assets/b853d08d-7322-48c7-94f3-585c3fc9bf7f" />

## Importing file to
* Using **Import Wizard** to select file to use.

<img width="870" height="362" alt="3 Import Dat Wizard" src="https://github.com/user-attachments/assets/0427b10a-ff4a-494d-882c-7f19344091a9" />

## Selecting File
* Browse for **file** to use.

<img width="820" height="682" alt="4  Locate File" src="https://github.com/user-attachments/assets/864f7b0c-735e-4e57-8d9b-67785c9d31e7" />

## Select Destination Table
* Select **Create new table** with **title name** & **file name**.

<img width="866" height="750" alt="5  Create New Table" src="https://github.com/user-attachments/assets/a3d6559e-c62f-4fae-b2ce-b836794a29f8" />

## Configure Setting
* Setting what **field type** each **column**.

<img width="829" height="698" alt="6  Confirm Columns And Field Types" src="https://github.com/user-attachments/assets/feb4be2b-ce65-44fc-aedc-d9a64404c25c" />

## Import Data
* **Import** data into the table.

<img width="870" height="709" alt="7  Import Data" src="https://github.com/user-attachments/assets/00fb175a-ecd7-4f49-8d49-2e282edbe9ec" />

## Import Results
* Confirmation shown of **data** imported.

<img width="825" height="693" alt="8  Import Results" src="https://github.com/user-attachments/assets/c1ad6f84-8121-455a-9429-ca05c3feb440" />

## Visual Of Table
* **Refreshing** the **Schema Tab** shows the **schema** & **tables**. 

<img width="158" height="248" alt="9  Refresh To Show Table" src="https://github.com/user-attachments/assets/52b6f2f0-2925-4a9f-ad22-e5097d677904" />

## SELECT Query
* A simple **SELECT statement** with the **output** table.

<img width="819" height="853" alt="10  Simple SELECT Query" src="https://github.com/user-attachments/assets/79b3fbb0-ae88-4a0e-926b-b075987c5bf9" />

## Create Staging Table
* Using **CREATE TABLE** statement to create a new table to manipulate data.

<img width="497" height="296" alt="11  CREATE Staging Table" src="https://github.com/user-attachments/assets/28504d26-9780-47e4-a1e6-7690d579ba51" />

## Staging Table View
* Using a **SELECT** statement and selecting the **staging table** in the **FROM** statement, shows no data in table.

<img width="679" height="296" alt="12  No Data" src="https://github.com/user-attachments/assets/c7563d4b-30b2-40b1-bfb0-d87d619e411b" />

## Inserting Data
* **INSERT** statement is used with **staging table**, followed by a **SELECT** statement and then using the **original table** in a **FROM** statement, **inserts** the **data** into the **staging table**.

<img width="811" height="652" alt="13  Insert Data" src="https://github.com/user-attachments/assets/c98740ad-a4d3-41ad-ae4b-633555d68d5c" />

## Creating Unique Row Numbers
* Firstly using **ROW NUMBER ()** function that **assigns** a **unique sequential integer**. Then using the **OVER ()** clause with **PARTITION BY** and selecting all the **columns**, adds them to the calculation. Using **AS** gives the column an name. As shown, the **table** has a **new column**, that identifies number of **unique values**.

<img width="1073" height="468" alt="14  Created Unique Row Numbers" src="https://github.com/user-attachments/assets/8f8172e7-cf1b-4178-99ce-8d3f1343c78a" />

## Using CTE To Remove Duplicates
*

<img width="973" height="541" alt="15  Created CTE To Filter" src="https://github.com/user-attachments/assets/d3d2e388-30b4-48c3-afb1-a4c6a2110c8e" />

## Checking Duplicates
*

<img width="1064" height="645" alt="16  Checking Duplicates" src="https://github.com/user-attachments/assets/fb292c98-1dea-4702-83d2-b9245b643f3f" />

## Shortcut to **CREATE** Statement
*

<img width="767" height="702" alt="17  Create Statment Shortcut" src="https://github.com/user-attachments/assets/7e169bdd-2973-48fd-af05-0db914f84a16" />

## Shortcut Output
*

<img width="766" height="421" alt="18  Create Shortcut Results, Changed Name" src="https://github.com/user-attachments/assets/53e726ce-a153-4186-b19c-b7fb008b3975" />

## Adding New Column
*

<img width="767" height="456" alt="19  Create  New Column" src="https://github.com/user-attachments/assets/31e79c55-93d0-4138-bddb-5d56e0eaae49" />

## No Data In Table
*

<img width="1112" height="825" alt="20  Empty Table" src="https://github.com/user-attachments/assets/2dfb9f41-9b91-4460-b18a-5ca932e12f48" />

## Searching For Duplicates
*

<img width="284" height="129" alt="21  Find Duplicates" src="https://github.com/user-attachments/assets/4fc25385-8713-4907-8a49-613954b09413" />

## Deleting Duplicates
*

<img width="292" height="141" alt="22  Deleting Duplicates" src="https://github.com/user-attachments/assets/2287a266-01b9-443f-bc35-2194215e6ae6" />

## Duplicates Removed
*

<img width="1080" height="461" alt="23  Deletion Results" src="https://github.com/user-attachments/assets/afaa1688-b124-4c73-a261-dd0839441184" />

## Removing Whitespace Around Text
*


## Updated Columns Without Whitespaces
*

<img width="450" height="688" alt="26  Update Results" src="https://github.com/user-attachments/assets/c0563e39-4931-4bd0-9925-f01291fc9287" />

## Identifying Specified Values
*

<img width="230" height="83" alt="27  Searching for company name" src="https://github.com/user-attachments/assets/38e60d58-ce33-4fd4-81d2-1d2ff8af3ee6" />

## Updating Value Names To Match
*

<img width="292" height="65" alt="28  Update Industy column data" src="https://github.com/user-attachments/assets/b3b789f7-0bce-4153-bd8a-96067da4500f" />

## Setting New Update To Table
*

<img width="304" height="368" alt="29  Update results" src="https://github.com/user-attachments/assets/95b880b3-b7b2-4b35-935b-ef5c10c5c2f9" />

## Removing Tailing Marks At The End Of Texts
*

<img width="481" height="105" alt="30  Removing tailing mark in column" src="https://github.com/user-attachments/assets/27557432-3e82-4d64-af69-ab20af147014" />

## Updated Values 
*

<img width="402" height="73" alt="31  Update removed trailing marks" src="https://github.com/user-attachments/assets/cfad889f-4886-4b2f-9a29-5b3d2746412d" />

## Checking Column Field Type
*

<img width="217" height="665" alt="32  Column definition" src="https://github.com/user-attachments/assets/ceefbdf2-f002-41cd-af5c-e99e912d0802" />

## Changing String To Date Type
*

<img width="315" height="303" alt="33  Changing String to Date with function" src="https://github.com/user-attachments/assets/242a2c4e-5c34-4b42-9ff8-c96aef99e199" />

## View All Columns With Data Types
*

<img width="206" height="211" alt="34  Columns and Types" src="https://github.com/user-attachments/assets/02f674f2-36bb-4b4d-94bf-aad85f6664e2" />

## Modify Data Types In Columns
*

<img width="251" height="61" alt="35  Modify Column" src="https://github.com/user-attachments/assets/f9f93686-92f0-4c11-b6db-0e40819f5e8e" />

## Data Type Changed In Column
*

<img width="207" height="225" alt="36  Date column type changed" src="https://github.com/user-attachments/assets/826d4946-f7aa-42e4-a392-ac25b56b0fd3" />

## Finding Null Values In Columns
*

<img width="388" height="315" alt="37  Finding Null Values in column" src="https://github.com/user-attachments/assets/27b56350-7efd-4145-8f32-4d5480bfb0a6" />

## Finding Null Values In Columns 2 Different Columns
*

<img width="455" height="332" alt="38   Finding Null Values in 2 columns" src="https://github.com/user-attachments/assets/9717f266-004f-4dcb-a961-e6f62a6dcd35" />

## Checking Column For Null Or Empty Values
*

<img width="219" height="96" alt="39  Column Null or Empty value" src="https://github.com/user-attachments/assets/6fbbc9d4-a320-4f83-b2c0-165b0431fb4f" />

## Using Join To Find Null Values
*

<img width="1656" height="423" alt="40  JOIN and results" src="https://github.com/user-attachments/assets/68415211-cff1-4c26-a57b-065985ca712e" />

## Delete Any Null Values Found
*

<img width="713" height="280" alt="41  Delete null values" src="https://github.com/user-attachments/assets/91eaa456-6c52-43e3-8124-4f4eb3eb2951" />

## Drop Column
*

<img width="293" height="56" alt="42  Drop Column" src="https://github.com/user-attachments/assets/f24e1311-dda6-440d-8de3-af481e5819c9" />

## Data Cleaned
*

<img width="821" height="326" alt="43  Cleaned Data" src="https://github.com/user-attachments/assets/3c0edf3e-74c5-4938-968a-efb4184c96cc" />
