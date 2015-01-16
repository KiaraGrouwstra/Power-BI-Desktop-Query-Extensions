# power-query-extentions
Power Query Functions  that you can use to make life easy-peasy


# Getting Started  
## Create a blank query
![New Blank Query](https://cloud.githubusercontent.com/assets/1501159/5770609/ce1c6c62-9ce1-11e4-92b4-fee8d60a6bb7.png)

## Name the query (We prefer PQ)
## Paste in the extension
![Create](https://cloud.githubusercontent.com/assets/1501159/5770648/52c12b38-9ce2-11e4-8a3e-63ac136a7c2c.png)

## Use it!   
 **=Table.AddColumn( GeographyTable, "State is Capitalized", each PQ\[IsUpperCase\]( \[State Abbrev\] ) )**