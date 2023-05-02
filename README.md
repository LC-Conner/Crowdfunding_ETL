# PROJECT 2


## Part 1
***
- Pulled the excel into the Jupyter Notebook
- Then we separated the category and subcategory columns
- Created a new DataFrame named new_df
- Identified the unique values in the new separated columns 
- Added prefixes to the category and subcategory
- Exported both dataframes into CSV files


## Part 2
***
- Created a new DataFrame named Campaign_df
- Converted the goal and pledged columns to a float
- Updated the format to the launhed_date and end_date columns to the datetime format
- Merged the Campaign DataFrame and removed the unwanted columns
- Once the data was clean we created a clean CSV


## Part 3
***
### Option 1
- Created a Contacts DataFrame
- Added a list of list of values to the DataFrame
- Split the names columns into 2 columns (first and last)
- Clean the dataframe by dropping unwanted files, and reorganizing columns
- Then the DataFrame was exported to a CSV

### Option 2
- Pulled the Contacts
- Extracted the contact ID number and change the contact_id column data type
- Then the name and emails from the contact_id column were spearated into their own columns
- The columns were reordered and the DataFrame was converted to a CSV file
- 

## Part 4
***
- Created a entity relationship diagram after looking through the CSVs to understand what columns exist and what columns overlap
- From the ERD (entity relationship diagram) we create a data base in pgadmin and separated tables according to each CSV.
- Imported the CSVs with primary keys first, as tables, and set the primary keys to each respective table.
- Then set the foreign keys to the lone table with foreign keys.
- Lastly we ran select statements for each table to see all of them are running within the database.
