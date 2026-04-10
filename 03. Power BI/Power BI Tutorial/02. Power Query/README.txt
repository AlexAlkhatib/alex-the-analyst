00. Import Excel File in Power BI
01. Check "Pivot Table" & "Purchase Overview"
02. Transform Data
03. Notice Columns 1...6 in Pivot Table 2022 (ABC) (1.2)
04. Clean Purchase Overview
05. Select first row with null values and click -> Remove Rows -> Remove Top Rows -> 2
06. Transform -> User First Row as Headers
07. 4/1/2022 click on 1.2 and change to fixed decimal number -> Replace Current ($)
08. Do the same for all dates
09. Filter Location -> Remove Empty
10. Right click on Products -> Filter -> Text Filter -> Does NOT contain -> Total -> OK
11. Click on Grand Total Column -> Remove Columns -> Insert
12. Select all dates columns -> Transform -> Unpivot Columns -> (Attribute : Value)
13. Change Attribute data type to Date
14. Rename Value to Product Cost
15. Rename Location to Store
16. Go to Pivot Table 2022
17. Right Click on the first row and make it Column Headers
18. Select All Months -> Transform -> Unpivot Columns
19. Home -> Close and Apply