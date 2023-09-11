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

In the "Fields" pane on the right, i selected the table i want to add the "Age Band" column to which is the bank full.

Clicked on the "Modeling" tab in the Power BI Desktop ribbon.

In the "Calculations" group, i clicked on "New Column."

In the formula bar that appears at the top, enter the following DAX formula:Age Band =
IF('YourTableName'[Age] <= 30, "Young",
    IF('YourTableName'[Age] <= 50, "Mid-aged", "Old")) 

![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/6d6da5e2-bd91-4154-8c32-acb2aa0828f0)


3. ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/55e9b818-44b8-4a6d-89ad-734cbac0baa1)

  ![image](https://github.com/Maris27/POWER-BI-TASK-3-4-5/assets/140453106/533dc5b6-c7af-4f03-b696-1cb4827596ae)
 

    



