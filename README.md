--PROJECT OVERVIEW--

In this project, we analysed the influence of study time, outside class activities, absent days, tutor involvement and parental supports on student grade so that the school management & parents can take neccesary actions to improve student score. We also compare the student based on the gender roles to observe which gender perform wll in exam. The visualization consist of various charts to oversee the student performance so that they can tackle the issue effectively.


--DATA CLEANING IN EXCEL--


Step 1: Check for duplicate rows:
i) Select table
ii) Click Data Tab
 iii) Click Remove Duplicates
iv) Tick all the check boxes

Step 2: Data Standardization
a) Capital/lower letters:
i) Add new column
ii) use function PROPER() to change all text in proper forms
b) Spelling check:
i) Select table
ii) Click Data Tab
iii) Click Filter to filter every column and check spelling errors
iv) Fix the error
c) Removing spaces:
i) Add new column
ii) use TRIM() to trim out unnecessary spaces between text
d) Date Format:
i) Select table
ii) Click Data Tab, Text to Column, Next (2x), column data format, select Date, then select format (date format), select destination
e) Currency format check:
i) change every currency format for number type data to integer format

Step 3: Categorizing Data
    i) Caterigorizing 'Study Time Weekly' & 'Absences' columns by adding new categorized columns using IF() functions.
    ii) This step will ease for data visualization.

Step 4: Change column values based on Dataset Info Provided. 
    - The raw data for some column is in numerical which difficult for stakeholders to understand.
    - Therefore, we need to change the values to more readable values based on Dataset Info provided.

Step 5: Copy the formatted value and paste values in original columns

Step 6: Remove Unwanted columns (eg: Formula columns)




--DASHBOARD OVERVIEW--

- The dashboard is visualized in Excel.
- The dashboard consist of various charts to visual the effect of study time, outside class activities, absent days, tutor involvement and parental supports on student grade.
- It also contains comparison of student grades based on gender roles.
- We can filter out student age, ethnicity and parental education through slicers to see in-depth about the student performance information.






  
