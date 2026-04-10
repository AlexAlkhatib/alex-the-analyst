01. Open Power BI and Load the three tables from the Excel File
02. Go to Model view
03. Double click any Relationship to edit -> Click on Sales(Cust ID) and Information(Customer ID) -> Save
04. Apocalypse Sales(Product ID) and Apocalypse Store(Product ID) -> Many to One -> Both -> Make this Relationship Active -> Save
05. Report view -> Customer Information -> State -> Visualizations -> Table
=== We want to see how many products were product in each state ===
06. New measure -> Measure = COUNT('Apocalypse Store'[Product ID])
07. Check measure to be Added to that table -> Refresh
08. Delete Relationships and build them from scratch (for demonstration purposes) 
09. Drag a column from one table and drop it in another one to create a new relationship