1. Right click Year -> Create -> Bins (Classes)
2. Size of bins = 5 -> OK
3. Get rid of Years in Columns and replace it with Year (Classes)
4. Right click on Year NULL -> Exclude
5. Right click on Total -> Quick Table Calculation -> Percent of Total
6. Rename Rows to : Percentage of Global Sales
7. Right click on Global Sales -> Create -> Calculated Field -> [Global Sales]-[EU Sales] -> OK
8. Rename to : Global Sales - EU Sales
9. Replace SUM(Global Sales) with the SUM(Calculated Field)
10. Drag both of them in Rows to compare