
# Blending Data Organization and Computation with Pandas NumPy


# PANDAS: 
Pandas is an open-source Python library primarily used for data manipulation and analysis. It offers easy-to-use data structures like DataFrames (two-dimensional labeled data) and Series (one-dimensional labeled data), making it simple to work with structured data efficiently. Pandas is especially popular for tasks like cleaning, filtering, reshaping, merging, and aggregating data.
* Key features: -
* Handling of tabular data(like spread sheet)
* Support for time line data
* Efficiently handling of missing data
* Powerful tools for data cleaning and transformation 

* Installation and import Pandas: -
   
   Write- “pip install pandas”
![Screenshot 2025-03-22 190121](https://github.com/user-attachments/assets/80c91317-900b-4c29-bbe3-1a7715cf756d)
Write – “import pandas as pd “
![Screenshot 2025-03-22 190627](https://github.com/user-attachments/assets/4201827c-0ac3-40ad-9280-63d1a737ee1a)
* Data Structures: -
Series: One dimensional array. Hold any datatypes (integers, strings, float etc.)
![Screenshot 2025-03-22 192028](https://github.com/user-attachments/assets/a521787a-d2b9-4f89-a454-365f996e032f)
![Screenshot 2025-03-22 193325](https://github.com/user-attachments/assets/f44d8daa-bcfe-4fac-bdc2-f79ad812d1e1)
Data frame: A data frame is two dimensional table -like data structure with rows and columns. It similar to a spreadsheet or SQL table
![Screenshot 2025-03-22 200406](https://github.com/user-attachments/assets/e38f206c-7837-434e-afe7-708f899d2425)
Accessing Data:-
 ![Screenshot 2025-03-22 201056](https://github.com/user-attachments/assets/60296eae-b1cc-42de-bf6a-f7a6d6798f14)
![Screenshot 2025-03-22 201831](https://github.com/user-attachments/assets/f969195f-aa1f-4670-8a40-4b69dff8e9b0)
![Screenshot 2025-03-22 202425](https://github.com/user-attachments/assets/5dfda84f-e2df-4aaf-8e81-7a328fb3e57b)

* Adding new column:-
Mentioned the new column name and also update the value
![Screenshot 2025-03-22 202909](https://github.com/user-attachments/assets/cddad282-aeea-490d-8427-84b0c19ed408)

* Filtering Data:
We are able find out specific data with proper condition 
![Screenshot 2025-03-22 230934](https://github.com/user-attachments/assets/e7ae0819-4c4f-4f26-89c5-96b6b184ebd1)

![Screenshot 2025-03-22 231336](https://github.com/user-attachments/assets/0672de81-c7e2-4e1f-89f8-c7b2dc3b6995)

* Describe:- 
Descriptive statistics include those that summarize the central tendency, dispersion and shape of a dataset's distribution, excluding NaN values.
Analyzes both numeric and object series, as well as DataFrame column sets of mixed data types. 
For numeric data, the result's index will include count, mean, std, min, max as well as lower, 50 and upper percentiles. By default the lower percentile is 25 and the upper percentile is 75. The 50 percentile is the same as the median.
![image](https://github.com/user-attachments/assets/1c041805-1a7c-4f6b-a175-d770ce3acd7c)

* Saving or Loading data:-
Choose the read file type according to the file type of local 
![Screenshot 2025-03-22 234953](https://github.com/user-attachments/assets/231ac174-3c84-44a6-99d9-8e9f50fc5554)
Import data location path from local 
![Screenshot 2025-03-22 235208](https://github.com/user-attachments/assets/40523c8b-5351-4328-a87e-7e70bb39a178)
Change all the ‘\’to ‘/’
![Screenshot 2025-03-22 235435](https://github.com/user-attachments/assets/8517ff86-6126-4a5d-88c5-9f85401e722c)
Specifically saving or loading a sheet from the excel: - need to mentioned the sheet name after file location path 
![Screenshot 2025-03-23 001057](https://github.com/user-attachments/assets/6299ddd9-d5b2-4edc-a32c-f527bc86cdd3)

* Data cleaning: -
![image](https://github.com/user-attachments/assets/f32b4aea-301f-42cc-af51-45ba5cf55ff7)
Identify the Missing Value :-

Isna:-Missing values are reflecting as True and others will be as False
![image](https://github.com/user-attachments/assets/0039fa23-71b1-441c-a93d-1b38878d7204)
Every column no. of missing values will be reflected 
Isnul:-![image](https://github.com/user-attachments/assets/fb35d806-5301-4667-b0a8-87df179480d7)
Notna:- opposite of Isna
![image](https://github.com/user-attachments/assets/a683954b-078b-49cd-948e-959689370a98)
Dropna:- Remove missing values.
![image](https://github.com/user-attachments/assets/239b4cac-14c9-433e-b4de-d20f34bc7f7b)
Fillna: To update the missing value in the data frame
![image](https://github.com/user-attachments/assets/d007c250-d6ac-4f4d-9c95-c1785de48848)
Rename:
Rename the column name
![image](https://github.com/user-attachments/assets/11e35800-4c65-46d6-bfe2-a3f68ff16e0c)
Replacing data from inside of data frame
![image](https://github.com/user-attachments/assets/07ebe264-de48-4f33-b23d-446b97b2c9db)

Astype: Specific Column can be reflect can be with specific data type 
![image](https://github.com/user-attachments/assets/623f9efe-cf34-417a-8108-8b6cd7325b82)
Upper/Lower case column:
Add  duplicate column with upper or lower case
![image](https://github.com/user-attachments/assets/767186e3-0141-4b8c-93ab-fd01a2e9e3c7)
Boolean :
Boolean (True/False) operations in Pandas, a popular Python library for data manipulation. Here's a quick guide:
![image](https://github.com/user-attachments/assets/0af705b6-bd91-4896-a5ab-961dc350f4b1)





