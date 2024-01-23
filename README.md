"# Football-Transfers-Analysis-in-Excel-Project"

#### Football data_Task1 – Database Review
Use the Football data_source.xlsx file to identify and fill in any missing data in the database for the 2021/2022 and 2022/2023 seasons. Take some time to review the database for errors and correct them.
1.	Go to the Database sheet, where you’ll find empty columns that need to be filled in by the information from the Countries sheet.
2.	The names of countries and continents in the Countries sheet is extracted using 'Text-to-Columns' feature in Data Ribbon.
3.	Next, find an incorrect year in the Season column. Create a header 'filter' from Data Ribbon and use 'Find and Replace' tool pressing 'Ctrl + H' to correct the year.
4.	The last task involves filling in the two Continent columns in the Database sheet. For this, use ‘VLOOKUP’ function.

The VLOOKUP function in Excel is a powerful tool for searching and retrieving data from a table based on a specified lookup value. The term "VLOOKUP" stands for "Vertical Lookup," and it is commonly used when you have a vertical list of data and want to find a corresponding value in the same row.

#### Football data_Task2 – Analyze the Aggregate Number of European Transfers
Create a table showing the total number of football transfers in and out of Europe during the two seasons under examination. We're interested in the net transfer balance. Does Europe, overall, import or export more players?
1.	To perform this analysis using Excel functions, add a new sheet and rename it to ‘European Transfers’. Create a table as asked in question.
2.	Use ‘SUMIFS’ function to get the total number of football transfers in and out of Europe during two seasons.
3.	Lastly, subtract total transfers outgoing from total transfers incoming to get Net Transfers during the two seasons.

    The SUMIFS function in Excel is used to sum values based on multiple criteria. It allows you to specify multiple conditions, and it adds up the values that meet all the specified         criteria.
