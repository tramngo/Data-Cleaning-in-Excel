# Excel-for-Analytics

## Tool: Excel
This project is designed from Benjamin Larson's Analytics4All YouTube tutorial: https://www.youtube.com/watch?v=WRk9t5yo5Zs

## Data Cleaning Actions
* Find duplicates
* Handle missing data
* Convert data
* Merge data sets

## Excel Formulas Used
<p>=IF(cell="","NO DATA",cell)</p>
<p>=TEXT(cell,”dddd”)</p>
<p>=VLOOKUP(reference value, lookup table, return column, Excel Match/Not Exact)<p>
<p>=RIGHT(cell,LEN(cell)-4)</p>
  
## Find duplicates
<p>Highlight duplicates cells with Conditional Formatting</p>
<p>Remove duplicates by using the Remove Duplicates option under Data tab</p>

## Handle missing data 
<p>Put in a placeholder by using IF statement</p>

## Convert data
<p>Insert new column next to date column for day of the week</p>
<p>Convert date to day of the week name using the TEXT function</p>

## Merge data sets
<p>1. Insert new column next to Service in Sheet 1</p>
<p>2. Name new column Price</p>
<p>3. Move table info from Sheet 3 onto Sheet 1 by using VLOOKUP function</p>
<p>4. Use nested function to remove LIC in license plate in Sheet 2</p>
<p>5. Replace new License Plate info onto Sheet 1</p>
<p>6. Insert two new columns next to Service in Sheet 1</p>
<p>7. Name two new columns Make and Model, respectively</p>
<p>8. Move table info from Sheet 2 onto Sheet 1 by using VLOOKUP function</p>

## Create Pivot Table
<p>Go to Pivot Table under Insert tab to create pivot table</p>
