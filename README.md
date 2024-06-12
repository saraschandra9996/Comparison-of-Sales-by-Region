Description:
The director of a leading organization seeks to compare sales between two regions and has tasked each region's operators with recording sales data for comparison. Upper management desires a dashboard to visualize the sales data, aiding in understanding performance differences and suggesting necessary improvements.

Objective: Assist the organization by creating a dashboard to visualize and compare sales between two selected regions.

Dataset: Sample Superstore

Steps to Perform:

1. Select Sample Superstore Dataset
   - Use the Sample Superstore Dataset for analysis.

2. Select Data
   - Utilize the Group by function from the Data Source Table to create a folder, organizing the data by Customer Name and Order ID.

3. Create a Hierarchy
   - Establish a hierarchy called Location for the variable Country.

4. Create Parameters:
   - Develop two parameters: Primary Region and Secondary Region, including all regions in the list. These parameters will represent the regions being compared.

5. Create Parameters for Primary and Secondary Regions**

6. Create Calculated Fields:
   - Create a Calculated Field for both the Primary Region and Secondary Region.

7. First Order Date:
   - Create a Calculated Field named First Order Date.

8. Create a Dashboard:
   - Arrange all sheets within the dashboard.
   - Partition the dashboard to display the following details for both the Primary Region and Secondary Region:
     - First Order Date
     - Total Sales
     - Average Sales per Order
     - Number of Customers
     - Number of Orders
     - Number of Products in Sales.
