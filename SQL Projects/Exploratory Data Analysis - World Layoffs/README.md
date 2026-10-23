# Layoffs - Exploratory Data Analysis

## MAX Function On Total Laid Off Column
* Shows the **total number** of those who got laid off in one go.

<img width="405" height="262" alt="1  MAX function total" src="https://github.com/user-attachments/assets/e2a11625-f67a-4acd-aaf6-72c04a07a9f9" />

## MAX Function On Total Laid Off Column And Percentage Laid Off
* This shows both the **total number** of those who got laid off in one go as well as **percentage** displayed as a **1** representing **10%**.

<img width="738" height="255" alt="2  MAX function percent" src="https://github.com/user-attachments/assets/97425d8c-83bd-4863-bfba-45f071884ccb" />

## WHERE clause
* Showing **all** results that **output** the required result **(1)**.

<img width="1299" height="1489" alt="3  WHERE clause" src="https://github.com/user-attachments/assets/e34f8e3d-3990-40ff-aa83-e8c88f4b7fab" />

## ORDER BY Total Laid Off Column
* Following on from the **WHERE** clause, adding **ORDER BY** & **DESC** to place all values in a **descending order**. 

<img width="1257" height="1487" alt="4  ORDER BY clause" src="https://github.com/user-attachments/assets/f4cf596c-00e7-4d39-91bc-6618169a211d" />

## ORDER BY Funds Raised Column
* Same as above just using the **funds_raised_millions** column.

<img width="1296" height="1488" alt="5  ORDER BY DESC funds_raised" src="https://github.com/user-attachments/assets/d3923d9b-7d75-416a-9b0f-773bb0036774" />

## SUM Function, GROUP BY Clauses By Company
* Selecting a **specified** column as well as using a **SUM()** function on a **column**. Then using the **GROUP BY** clause on a specified column to group to the rows together. Finally using a **ORDER BY** clause using **2** for the column to look at, then placing the results in a **descending order**.

<img width="507" height="639" alt="6  SUM function total_laid_off" src="https://github.com/user-attachments/assets/34d9c005-3e34-4401-88b9-f51e11787ac0" />

## MIN & MAX Functions On The Data Column
* Outputs **Lowest** and **Highest** date result.

<img width="466" height="271" alt="7  MIN MAX functions date" src="https://github.com/user-attachments/assets/f719fb97-bf13-44fc-86db-59533087d29d" />

## SUM Function, GROUP BY Clauses By Industry
* Same as the **SUM Function** and **Group By Company** syntax. Output shows the amount of **individuals laid off** by **industry** type.

<img width="505" height="630" alt="8  Industry layoffs" src="https://github.com/user-attachments/assets/64767c4a-67c8-4a24-b6bc-f38861bd5118" />

## SUM Function, GROUP BY Clauses By Country
* Same as the **SUM Function** and **Group By Company** syntax. Output shows the amount of **individuals laid off** by **country**.

<img width="503" height="680" alt="9  Country layoffs" src="https://github.com/user-attachments/assets/38a26e15-a53f-4d86-b8cc-0fd181460eb9" />

## SUM Function, GROUP BY Clauses By Date
* Same as the **SUM Function** and **Group By Company** syntax. Output shows the amount of **individuals laid off** by **date**.

<img width="494" height="524" alt="10  Date layoffs" src="https://github.com/user-attachments/assets/14ca08b5-8325-4e92-94b4-35b6d57486d9" />

## YEAR Function with SUM Function, GROUP BY Clauses By Date
* Same as the **SUM Function** and **Group By Company** syntax. Added **YEAR function** looking at the **date** column.  Output shows the amount of **individuals laid off** by **date**. Using a **ORDER BY** clause using **1** for the column to look at, then placing the results in a **descending order**
  
<img width="548" height="399" alt="11  YEAR function" src="https://github.com/user-attachments/assets/99c0895e-cb5b-4f96-b0b9-1d1ea4f0b75c" />

## SUM Function, GROUP BY Clauses By Stage
* Same as the **SUM Function** and **Group By Company** syntax. Output shows the amount of **individuals laid off** by **date**.

<img width="477" height="670" alt="12  Stage total_layoffs" src="https://github.com/user-attachments/assets/77a8004d-0b6a-4a74-a01e-2b4fcf94b317" />

## Total Layoffs By Month
* Using **SUBSTRING** function with the **column** desired, followed by the starting position **(1)** & then the number of strings to extract **(7)**. Then using **AS** to give the function a **name**. A **WHERE** clause is used on the **SUBSTING()** function and setting the **condition** to **IS NOT NULL**. The output shows a total number of **individuals laid off** by **month**.

<img width="802" height="779" alt="13  Layoffs Per Month" src="https://github.com/user-attachments/assets/72f91c2e-4d3c-48c9-82a1-e07fb44bdc03" />

## Rolling Total Through CTE
* To create a rolling total using a **CTE**, the previous syntax was used inside an **AS** clause and a **()**. Outside the **CTE** a **SELECT** clause focusing on **specified columns** is used, then followed by a **SUM()** along with a **OVER()** which uses **ORDER BY** on a **specified column** & renamed with **AS**. Finally ending with a **FROM** clause calling the **CTE** made before. The output shows the **total laid off** by **month & year** then adding each result to a **rolling total**.

<img width="898" height="858" alt="14  Rolling Total" src="https://github.com/user-attachments/assets/9bc80006-6323-4045-a368-5b40763a1725" />

## Layoff's By Company 
*  Looking at **Company** column, **date** by **YEAR** & also **SUM** of **total_laid_off** column. Then using **GROUP BY** 2 columns. Finally **ordering by** the **3rd** column.

<img width="661" height="639" alt="15  Layoff By Company By Year" src="https://github.com/user-attachments/assets/a1d55d83-8c4f-4ca4-bc91-4d350753915b" />

## DENSE RANKING Function 
* Using a double **CTE** to find show the **ranking** of who laid off the most. Using the **DENSE RANK()** to assign a **rank** to **each row**. The output shows the **company** names, **years** the action took place, **total** number of individuals laid off and also the **ranking** of each result.

<img width="939" height="1124" alt="16  Dense Ranking" src="https://github.com/user-attachments/assets/e270762c-5b28-4f84-8f59-51e1e107c880" />


