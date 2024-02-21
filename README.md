

# Banking Domain - Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/0161dc70-0f9f-4911-a0dc-53341bae513d/ReportSection

## Overview

The TechnoEdge Customers Banking Details dataset contains information on customer’s banking details, including their customer ID, name, surname, gender, age, country, state, job classification, marital status, account type, date joined, balance, house loan, and other loan details. The dataset appears to be focused on the banking and financial activities of TechnoEdge customers.



### Steps followed For Data Cleaning

- Step 1 : Load data into Power BI Desktop, dataset is a excel file.
- Step 2 : Open power query editor & in view tab under Data preview section Use the "Change Type" option in Power Query to alter data types for each column.
- Step 3 : Use the "Transform Data" tab and the "Capitalize Each Word" option to display the "Name" column in capitalized format for each word.
- Step 4 : Use the "Add Column" tab and the "Merge Columns" option to combine the "Name" and "Sir Name" columns using a space separator.
- Step 5 : Use the "Remove Duplicates" option in Power Query to remove duplicate values from the dataset. 
- Step 6 : Use the "Transform Data" tab and the "Remove Rows" option to select the "Remove Blank Rows" option to remove any blank rows from the dataset.
- Step 7 : Use the "Combine Data" tab and the "Merge Queries" option to join the bank details with the customer details based on the customer ID.
- Step 8 : Access the "Transform Data" tab in Power Query and choose the "Date. Year" function to extract the Day from a date column.
- Step 9 : Use the "Add Column" tab and the "Round" option to round up the total balance to the nearest whole number.

### Data View

To show geographic data with its categories like city, country, state, and region, use Power BI's map visual. It's an easy and effective way to analyze and display geographical information.

### Visual Insights

Step 1: We will use Card visual to display the count of the customers and the total balance amount. Drag and drop the "Count of Customer" and "Sum of Balance Amount" fields onto the card visual in the report.

Step 2: We will use the slicer to filter customer names in the report. Add the "Customer Names" field to the slicer and use it to filter the report by customer name.

![Customers](https://github.com/Vishal29PP/Test/assets/160697627/be45f227-6e30-4764-9aa6-3c30bb7bfe79)
           
Step 3: We will use Pie Chart to display the account types and their total balance amount. Add the "Account Type" field to the legend and the "Sum of Balance Amount" field to the values in the pie chart.

![Pie Chart](https://github.com/Vishal29PP/Test/assets/160697627/c975740d-1930-4814-9fe2-1f43faaa119c)

Step 4: Now then, We will use Donut Chart to show the distribution of balance amounts by gender. Add the "Gender" field to the legend and the "Sum of Balance Amount" field to the values in the donut chart.

![Donutchart](https://github.com/Vishal29PP/Test/assets/160697627/a1b4c3a2-7805-4e6c-8a04-2da2c8d7e3fb)

Step 5: Now, We will use Stacked Bar Chart to display the total balance amounts by marital status.Add the "Marital Status" field to the Y-axis and the "Sum of Balance Amount" field to the X-axis in the stacked bar chart.

![Stacked Bar chart](https://github.com/Vishal29PP/Test/assets/160697627/939eda8d-9fab-4c84-902c-67c852c9448a)

Step 6: Now we will use Stacked Area Chart to visualize the total balance amounts by job classification and state. Add the "Job classification" field to the X-axis, the "Sum of Balance Amount" field to the Y-axis, and the "State" field to the legend in the stacked area chart.

![Stacked Area Chart](https://github.com/Vishal29PP/Test/assets/160697627/510fc331-7cc1-49dd-b3dd-373f756644ef)

Step 7: We will make a new "Age group" Column in which we will group the age numbers.
Here is the grouped column.

![Age](https://github.com/Vishal29PP/Test/assets/160697627/e5b50359-48d6-4959-817c-2de2cbd5f2fb)

Step 8: Use Clustered Column Chart to view the number of customers by age group. Add the "Age group" field to the X-axis and the "Count of Customer ID" field to the Y-axis in the clustered column chart.

Step 9: Use the text box visual and insert the logo image and type the company name as the text.

![PowerBi capstone project (Banking Domain)_page-0001](https://github.com/Vishal29PP/Test/assets/160697627/dec88590-f80d-49ad-abcb-8c7d6f5f443c)
