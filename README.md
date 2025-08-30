# Data_Analysis_Process_on_Medical_Data_Of_Testing_Of_Medicine
Here in this notebook, I am explaining all the possible ways to perform analysis on data like Data Accessing and Data Cleaning.

In the data, majorly there are two types or error found -
-- 1. Dirty Data -> Data that have quality issue. Like Duplicated Data or missing or corrupt or inaccurate data
-- 2. Messy Data -> Data that have tidyness issues. Untidy data has structural issue like Each variable froms a column or each 
                    observation forms a row. etc.

Steps for approaching data and to about what i learnt in this notebook is 
1. Write a summary of the data like what are columns indicating what is the objective of data.
2. Write column description of each column so that anyone can read the file which don't know about data get some info about it.
3. Perform assesment by MANUAL(Looking through out the data manually in google sheets.) and PROGRAMMATIC (By using pandas function such as info(),
   describe(),sample().

## NOTE -> Assessing data is an iterative process.
## Data Qualtiy Dimensions  - 
                              . Completeness -> is Data Missing?
                              . Validity -> is data invalid -> negative height -> duplicate patient_id 
                              . Accuracy -> data is valid but not accurate -> weight -> 1Kg 
                              . Consistency -> both valid and accurate but written differently -> New York as NY

# Order of Severity ->
                    - Completeness <- Validity <- Accuracy <- Consistancy 

## Data Cleaning Order - 
                          1. Quality -> Completeness(Handling Missing Values)
                          2. Tidiness 
                          3. Quality -> Validity
                          4. Quality -> Acuracy 
                          5. Quality -> Consistency 
                          
 
## Steps involved in Data cleaning ->
                                      1. Define
                                      2. Code 
                                      3. Test

                    
