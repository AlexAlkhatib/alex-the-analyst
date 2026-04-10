01. Load dataset in Power BI (Apocalypse Sales, Apocalypse Stores)
02. Report -> Right click Apocayplse Sales -> new measure : Count of Sales = COUNT('Apocolypse Sales'[Order ID]) -> Enter
03. Check (Count of Sales and Customer) -> Show as a table
04. Create a new report -> Check Apocalypse Store -> Product name
05. Right lick Apocalypse Sales -> new measure -> Sum of Products Sold = SUM('Apocolypse Sales'[Units Sold])
06. Check the new created measure
07. Right click on Stores -> new measure -> Profit = (SUM('Apocolypse Store'[Price]) - SUM('Apocolypse Store'[Production Cost])) * SUM('Apocolypse Sales'[Units Sold])
08. Create a new table -> Check Profit and Customer
09. Table view -> Apocalypse Store -> New column -> Profit Column = (SUM('Apocolypse Store'[Price]) - SUM('Apocolypse Store'[Production Cost])) * SUM('Apocolypse Sales'[Units Sold])
10. Create a new column : Profit Column SUMS = Profit Column SUMX = SUMX('Apocolypse Sales', ('Apocolypse Store'[Price] - 'Apocolypse Store'[Production Cost]) * 'Apocolypse Sales'[Units Sold])
11. Apocalypse Sales -> New Column -> Day of Week = WEEKDAY('Apocolypse Sales'[Date Purchased], 2)
12. New Column -> Order Size = IF('Apocolypse Sales'[Units Sold] > 25, "Big Order", "Small Order")
