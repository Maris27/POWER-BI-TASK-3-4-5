# Task 3

![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/55dd7204-e51f-462d-9af9-75030bde8ae0)



# TASK FOUR 

In task four we were asked to carry out the following below using the Bank Term Subscription Dataset

1. Create a measure for the ‘Average age of depositors’
2. Create a new column named ‘Age band’ containing the following;
‘Young’ for ages below 30
‘Mid-aged’ for ages between 30 and 50
‘Old’ for ages above 50
3. Create a measure calculating the total balance for:
Job: Technician
Marital: Single and Married
4. Create a measure to get the number of depositors on Loan



1. ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/48cf3495-c8ae-46e9-b1d1-ecaa9d2f7a24)



2. in answering question 2 i followed this steps.

step 1 In the "Fields" pane on the right, i selected the table i want to add the "Age Band" column to which is the bank full.
step 2 Clicked on the "Modeling" tab in the Power BI Desktop ribbon.
step 3 In the "Calculations" group, i clicked on "New Column In the formula bar that appears at the top, enter the following DAX formula
:Age Band =IF('YourTableName'[Age] <= 30, "Young", IF('YourTableName'[Age] <= 50, "Mid-aged", "Old")) 

![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/6d6da5e2-bd91-4154-8c32-acb2aa0828f0)


3. ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/55e9b818-44b8-4a6d-89ad-734cbac0baa1)

  ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/533dc5b6-c7af-4f03-b696-1cb4827596ae)

4. followed the same step in question 2 in answering this ,only used a different syntax
   Total balance for single

    ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/6c6f2382-c26b-45c2-9079-1d3b80a551a3)


   Total balance for married

   ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/2dabe9ce-4c02-4491-8f04-90be40156829)


   Therefore the Total balance for single & married is shown belown

   ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/49c82696-5b03-47ab-a485-f55f2f6ff706)



5. used the synthax as shown below to calculate the total depositors on Loan

![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/398c0731-d598-4103-bb73-58f2a854916c)


Therefore the total depositors on loan is 

![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/fa518a85-bcf3-492f-8327-a530180c2ed7)














# TASK FIVE



   

   

 

    



