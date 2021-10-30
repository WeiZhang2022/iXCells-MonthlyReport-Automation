# iXCells-MonthlyReport-Automation

### The purpose of this project
1. Update current script for file 'monthly sales report-googlesheet.ipynb' based on the change of Googlesheet. 
2. Design an analytic report with visualization
3. Refine the entire automation process


### Script update
1. New column 'New customer': 'Yes' or 'No'. Need to remove the duplicates for those orders with multiple items. 
2. New column 'Completed': 'Yes', 'Yes-replacement', 'Pending', 'Cancelled', and 'Delivered date scheduled'. Consider 'Yes' and 'Delivered date scheduled' as new orders. 


### Analytic report 
1. New customer 
2. Top customer 
3. Top product 
4. International Orders - distribution, customer and product 
5. Comparison - current month vs previous month 


### Refine automation process 
1. Fix Quartzy data export issue due to the change of ID
2. Figure out it is feasible to set a time to auto run the reports.

### Automation Process
1. Get inventory data from Quartzy. Using 'Quartzy_automation.ipynb' file. 
2. Clean inventory data and generate the report. Using 'monthly inventory.ipynb' file
3. Download the monthly sales records from google sheet using the link below. The digits should be changed. 
https://docs.google.com/spreadsheets/d/1BNtwHjC81NS4UThi1QABrlvpoNFTSuILSxG8dmSSk3A/export?format=xlsx&gid=439584568
4. Clean sales data and generate the report. Using 'monthly sales report-googlesheet.ipynb' file
5. Update sales table. Using 'sales_table_update.ipynb' file. 
