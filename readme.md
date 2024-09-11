# Bike Buyers dataset cleaning and visualization with Excel

[Bike Buyers Dataset.xlsx](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Bike_Buyers_Dataset.xlsx)

Dataset cleaning, exploration and visualization.

Step 1:

Created new sheets after loading the dataset. 

1. Working Sheet: a copy of the raw data, and where we will do most of the work.
2. Pivot Table
3. Dashboard

![Screenshot 2024-09-11 at 2.53.20 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_2.53.20_PM.png)

Step 2: 

Cleaning the data.

1. Started by applying filters to all columns and quickly look through to see if we can spot any issues.
2. Removing duplicates: by selecting the data, and then using the ‘Remove Duplicates’ option.
    
    ![Screenshot 2024-09-11 at 2.56.35 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_2.56.35_PM.png)
    
3. Making shortcuts in Column B and C more readable
    
    ![Screenshot 2024-09-11 at 4.48.06 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_4.48.06_PM.png)
    
    ![Screenshot 2024-09-11 at 4.49.15 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_4.49.15_PM.png)
    
4. Make the currency column more readable.
    
    ![Screenshot 2024-09-11 at 4.52.15 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_4.52.15_PM.png)
    
5. Put ages values into brackets and create a new column to be used later. And an easy way to do this is by using the IF function.
    
    ![Screenshot 2024-09-11 at 7.02.47 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_7.02.47_PM.png)
    

Step 3: 

Creating the pivot table to use it to create dashboard. 

We want to explore a few ideas in the dashboard.

1. The income of those who bought or didn’t buy a bike. 

    
    ![Screenshot 2024-09-11 at 7.45.32 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_7.45.32_PM.png)
    
    Created a chart to show that data.
    
    ![Screenshot 2024-09-11 at 9.10.49 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_9.10.49_PM.png)
    

1. Distance to work for those who did purchase and those who didn’t purchase a bike.
However, when grouping the data, we notice that 10+ miles is in the middle of the range instead of at the end. 
    
    ![Screenshot 2024-09-11 at 9.16.20 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_9.16.20_PM.png)
    
    In order to fix that, we’ll change it in the worksheet. 
    
    ![Screenshot 2024-09-11 at 9.18.04 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_9.18.04_PM.png)
    
    ![Screenshot 2024-09-11 at 9.24.03 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_9.24.03_PM.png)
    
2. Age brackets
    
    ![Screenshot 2024-09-11 at 9.34.23 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_9.34.23_PM.png)
    

Step 4: creating the dashboard

1. Started by copying the charts we created in the pivot tables sheet into the dashboard sheet. 
2. Cleaned the dashboard by removing the grid lines (Select sheet > View > Uncheck gridlines).
    
    ![Screenshot 2024-09-11 at 9.40.59 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_9.40.59_PM.png)
    
3. Created a header by selecting the portion we want to make our header, give it a color, “Merge and Center” from the home menu. Then align the tiles/charts to the way we want to display them within the dashboard. 

    
    ![Screenshot 2024-09-11 at 9.52.44 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_9.52.44_PM.png)
    

Step 5: adding more functionality to the dashboard by adding slicers.

Select the tile you want to add the slicer to > Insert Slicer > Select slicer from the list. If you want to add it to multiple charts, then select the slicer, then report connections and select the pivot tables corresponding to the chart you want to link the slicer to.

![Screenshot 2024-09-11 at 10.15.55 PM.png](Bike%20Buyers%20dataset%20cleaning%20and%20visualization%20wit%20dfe8ead20ef04902bd2dacb6ce5ceff8/Screenshot_2024-09-11_at_10.15.55_PM.png)