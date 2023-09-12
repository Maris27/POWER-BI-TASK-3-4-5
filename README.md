# Task 3


We were asked to Create a tracking DASHBOARD for a bank using the ‘Bank Term Deposit Subscription’ dataset provided.

First thing i did was to load the data set into the Power Bi, checked out for null values also checked if the data types of the columns were okay, then i used the DAX function to get the average age of the depositors  and also the average balance.
Next thing was to choose an approriate color for the background and canvas before i started creating visuals on it.

I created 5 KPIs from the dataset which are
1. The total balance of depositors

2. The total depositors on Loan

3. Average balance

4. Average Age of depositors

5. Different Job for depositors.


I used the card visual to analyze the KPI's as shown below.


![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/55dd7204-e51f-462d-9af9-75030bde8ae0)




# TASK FOUR 

In task four we were asked to carry out the following below using the same data set in Task 3.

1. Create a measure for the ‘Average age of depositors’

2. Create a new column named ‘Age band’ containing the following;

‘Young’ for ages below 30

‘Mid-aged’ for ages between 30 and 50

‘Old’ for ages above 50

3. Create a measure calculating the total balance for:

Job: Technician

4. Marital: Single and Married

5. Create a measure to get the number of depositors on Loan



     # ANSWERS

  ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/48cf3495-c8ae-46e9-b1d1-ecaa9d2f7a24)



2. in answering this i followed this steps.

step 1. In the "Fields" pane on the right, i selected the table i want to add the "Age Band" column to, which is the bank full.

step 2. Clicked on the "Modeling" tab in the Power BI Desktop ribbon.

step 3. In the "Calculations" group, i clicked on "New Column In the formula bar that appears at the top, enter the following DAX formula

:Age Band =IF('bank-full'[Age] <= 30, "Young", IF('bank-full'[Age] <= 50, "Mid-aged", "Old")) 


 ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/6d6da5e2-bd91-4154-8c32-acb2aa0828f0)







3. followed the same step in question 2 in answering this ,only used a different syntax.


    Total balance for single

    ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/6c6f2382-c26b-45c2-9079-1d3b80a551a3)



    Total balance for married

   ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/2dabe9ce-4c02-4491-8f04-90be40156829)


   Therefore the Total balance for single & married is shown belown

   ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/49c82696-5b03-47ab-a485-f55f2f6ff706)



4. Followed same steps in question 2 but used a different formular as shown belown.

 ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/55e9b818-44b8-4a6d-89ad-734cbac0baa1)

  ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/533dc5b6-c7af-4f03-b696-1cb4827596ae)







5. used the synthax as shown below to calculate the total depositors on Loan

![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/398c0731-d598-4103-bb73-58f2a854916c)


Therefore the total depositors on loan is 

![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/fa518a85-bcf3-492f-8327-a530180c2ed7)














# TASK FIVE



   

   

 

    



