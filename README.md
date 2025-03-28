
# Blending Data Organization and Computation with Pandas, NumPy,Matplotlib


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
Sort: -
If "ascending order" is set to false, the data frame will be displayed in ascending order. Conversely, if it is set to true, the data frame will be shown in descending order.

![image](https://github.com/user-attachments/assets/95176efd-2f93-4a72-a7c9-5ea95d0dfce0)

* Index:-
set_index()- Changes the current index to a specified column or set of columns.

![image](https://github.com/user-attachments/assets/0fb23edf-1dd4-4aba-aa23-ad120bd37fa1)

reset_index(): Resets the index to the default integer index.

![image](https://github.com/user-attachments/assets/2ed578b5-3397-4354-9676-0bbcdf858434)

sort_index(): Sorts the data by its index.
![image](https://github.com/user-attachments/assets/d9470469-5a91-4082-8aee-2152b1b8a6d8)

Query Method :-
The query() function allows you to use a string-based query expression to filter data.

![image](https://github.com/user-attachments/assets/9ca73949-dd2d-4f0b-90ba-bc10b90e6e07)

* Comprehensive Guide to Data Analysis and Aggregation: -
   i)Descriptive statistics

   ii)Window functions

   iii)Cross-tabulation

   iv)Advanced aggregation 

Creating a data frame based on date, product, sales, quantity, and region.

![image](https://github.com/user-attachments/assets/248ec058-281f-41d1-8e13-50e6033420e1)
 i)Descriptive statistics

summary of descriptive statistics for two variables: Sales and Quantity. Here's what each metric tells us:
•	Count: Total number of data points (6 for both columns).
•	Mean: The average value (225 for Sales, 22.5 for Quantity).
•	Std (Standard Deviation): Measures the spread of the data around the mean (Sales varies by ~93.54, Quantity by ~9.35).
•	Min: The smallest value in the dataset (100 for Sales, 10 for Quantity).
•	25%, 50%, 75%: Percentiles, which divide the data into quarters:
o	25%: 25% of the data is below this value (162.5 for Sales, 16.25 for Quantity).
o	50% (Median): The middle value when data is sorted (225 for both columns).
o	75%: 75% of the data is below this value (287.5 for Sales, 28.75 for Quantity).
•	Max: The largest value in the dataset (350 for Sales, 35 for Quantity).

![image](https://github.com/user-attachments/assets/72f24fee-ea09-44fe-a02e-66ea7a43aaf9)

b. Correlation and Covariance (corr, cov)
Correlation measures the relationship between two variables, while covariance measures how two variables change together.
* Correlation matrix
The correlation between Sales and Quantity is also 1.0, indicating a perfect positive correlation. This means as Sales increase, Quantity increases proportionally (and vice versa).

![image](https://github.com/user-attachments/assets/eb0ab19f-8121-4d49-8d25-fdd7c1bddd98)

* Covariance matrix

•  The covariance of Sales with itself is 8750.0, representing the variance within the Sales variable.

•  The covariance between Sales and Quantity is 875.0, showing a positive association—an increase in Sales corresponds to an increase in Quantity.

•  The covariance of Quantity with itself is 87.5, indicating the variance within the Quantity variable.

![image](https://github.com/user-attachments/assets/526fb34a-7cd8-42da-b24c-28bd76d2b5c1)

c. Counting Unique Values (value_counts)
The value_counts() function counts the occurrences of unique values in a column.

![image](https://github.com/user-attachments/assets/8d62ff76-d649-4af6-959a-eb5e39e86142)

2. Window Functions
Window functions perform calculations over a sliding window of rows.
a. Rolling Windows (rolling)
Rolling windows compute statistics over a fixed-size window of rows. Commonly used for moving averages, sums, or standard deviations.
![image](https://github.com/user-attachments/assets/2b195f79-ea27-43c3-9c3a-cd430f7fa4ca)

b. Expanding Window
This is a cumulative sum of Sales, considering all rows up to the current row.
![Screenshot 2025-03-24 120025](https://github.com/user-attachments/assets/f68c1a69-5be7-4d7b-9e20-9b882f4ad6c2)
3. Cross-Tabulation (crosstab)
Cross-tabulation is used to summarize the relationship between two categorical variables.
![image](https://github.com/user-attachments/assets/8c563eda-0b1e-4ab8-a2f4-a7ac7918428e)
4. Advanced Aggregation (agg)
This function allows you to apply multiple aggregation functions to columns.
![image](https://github.com/user-attachments/assets/f663a0a1-2413-49d0-8e50-33dd9f782603)

## Numpy :-
NumPy (short for "Numerical Python") is a fundamental library in Python for numerical and scientific computing.
![image](https://github.com/user-attachments/assets/5c5591ce-0c2a-4786-b6ad-4bf123e009bb)
![image](https://github.com/user-attachments/assets/a60bc81d-d058-432b-9439-dad3e81ae937)
To check the name of numpy formulas.
![image](https://github.com/user-attachments/assets/fcc2a60e-fe87-48d2-b0c3-ac79c037126b)

Array:-
Array is a collection of elements
np.array
![image](https://github.com/user-attachments/assets/645e65de-df09-47ca-a79d-488165b33ff5)
np.zeros
![image](https://github.com/user-attachments/assets/5403e4a3-d572-4f26-b890-a555a19b08da)
This looks like a 5x8 matrix filled with zeros, which is a great way to initialize arrays for numerical computations or placeholder data.
Np.ones
![image](https://github.com/user-attachments/assets/152bee82-e3e1-4d80-abc5-123ef592f0df)
one-dimensional array there, and it's likely you're exploring operations with arrays. Here's how you can create it using NumPy:
python
![image](https://github.com/user-attachments/assets/2165497a-665e-4051-b5e5-9b6f8275ead3)
np.linspace():-

It looks like you have a NumPy array with values that increase incrementally!

![image](https://github.com/user-attachments/assets/77781962-2fcd-4133-b0af-682a768b264c)
2D dimensional array :-

![image](https://github.com/user-attachments/assets/ec859330-d720-4087-afe4-9e4b83a0f5a0)

It seems you're indicating the shape of a 2D array. In NumPy, the shape of an array tells you its dimensions—in this case, it's a matrix with 2 rows and 3 columns.

Find out the data frame type :-
![image](https://github.com/user-attachments/assets/7216553d-a71d-400b-b5ab-2ec26ed0a5fa)

Find out the elements of array:-

The total size of the elements in your array represents the number of elements it contains. In this case, the shape (2, 3) indicates 2 rows and 3 
columns
![image](https://github.com/user-attachments/assets/d1a1a0b0-fdc0-4d48-84bf-1d6cbec19ac9)
Number of dimensions:

A 2-dimensional array, like our example, has two dimensions: rows and columns.

![image](https://github.com/user-attachments/assets/89737074-8fbd-4d9e-949a-c62bc23aaf02)


* Mathematical Operator

![image](https://github.com/user-attachments/assets/7cd55c94-a2e0-4f58-8a51-c827975b64a0)

i) Addition:- NumPy performs element-wise addition. If the arrays have the same shape, corresponding elements are added.

ii) Subtraction:- Element-wise subtraction is performed. Each element of the first array is subtracted by the corresponding element of the second array.

iii) Multiplication:NumPy performs element-wise multiplication, which multiplies corresponding elements together.

iV) Division: NumPy divides elements of the first array by the corresponding elements of the second array.


![image](https://github.com/user-attachments/assets/7a1d1ca5-1814-49e0-a346-c87c837295b6)

i) Square Root (np.sqrt):-The np.sqrt():- function computes the square root of each element in an array. It works element-wise on arrays and returns the result.
ii) Exponentiation (np.exp):- The np.exp() function calculates the exponential of each element in an array.

![image](https://github.com/user-attachments/assets/a99e24d3-f2e3-48f1-a119-9b2cc04e2995)

i) Sum: Adds all elements together.

ii)Max: Finds the largest value in the array.

iii)Min: Finds the smallest value in the array.

iv)Variance: Measures the spread of the data.

v)Sum Array: computes the sum of elements in an array, either across all elements or along a specified axis in the case of multidimensional arrays.

* Logical Operator: -

In NumPy, logical operators are used to perform element-wise logical operations on arrays. These operators help you to compare arrays and obtain Boolean results (True or False) for each element.
Some of the commonly used logical functions in NumPy include:

![image](https://github.com/user-attachments/assets/1f1ae0d2-ee1e-417c-90ae-9b77702e6cdc)
The > and < operators are applied to each element in the array, creating a new Boolean array where the condition is evaluated for each element. These Boolean arrays can be used for filtering or masking data.

* Vstack Array:

 In NumPy, vstack (vertical stacking) is used to stack arrays vertically, meaning along the first axis (axis=0). It combines arrays into a single array where the arrays are added as new rows.
 ![image](https://github.com/user-attachments/assets/3f9be29a-8160-4916-9ead-485e7bf0eb00)
This combines all the arrays vertically (adding each as a new row) into a 2D array.

* Hstack: 

The hstack function in NumPy horizontally stacks arrays, meaning it joins arrays along the second axis (axis=1 for 2D arrays). It appends arrays side by side, provided they are compatible in dimensions.

![image](https://github.com/user-attachments/assets/54e54920-464d-4360-9f6d-52c3480ed99e)

* Dstack:

 In NumPy, dstack (depth stacking) is used to stack arrays along the third dimension. This means the arrays are added "depth-wise," creating a 3D array. It's commonly used when you need to combine arrays into layers.

![image](https://github.com/user-attachments/assets/baedf188-cd80-4ac1-86e7-b1daad448ddc)

* Concatinate:

 In NumPy, concatenation refers to joining two or more arrays along an existing axis. You can use the numpy.concatenate function for this purpose.

![image](https://github.com/user-attachments/assets/ec468deb-3f12-4137-b24d-c61798f2995d)
axis=0: Combines arrays vertically (adds rows). The number of columns must match.
axis=1: Combines arrays horizontally (adds columns). The number of rows must match.


* Splitting:- 

In NumPy, splitting refers to dividing an array into multiple subarrays
![image](https://github.com/user-attachments/assets/76d6bcab-b141-4819-be00-80907bf98314)

numpy.split: Splits an array into multiple subarrays along a specified axis.

numpy.hsplit (Horizontal Split): Splits an array into subarrays along the columns

numpy.vsplit (Vertical Split):Splits an array into subarrays along the rows

numpy.dplit (dimension split): The dsplit function in NumPy is specifically designed to split arrays along the third dimension (depth) of 3D arrays.  

![image](https://github.com/user-attachments/assets/ccf8186e-bc7c-4d37-8470-2124ac488968)

* Transpose:-

In NumPy, the transpose of an array flips its axes. Specifically, rows become columns and columns become rows.
![image](https://github.com/user-attachments/assets/5bfcb6c6-a9dc-4d47-a4ea-f7ae38dc2904)

* Swapaxes:-

 The numpy.swapaxes function allows you to interchange two axes of an array. This is particularly useful for reshaping or reorganizing multidimensional arrays without changing the data.

![image](https://github.com/user-attachments/assets/91b71249-fe04-434a-a4bb-ad6e58f26821)


# Matplotlib in Python
Matplotlib is a popular Python library used for data visualization. It allows users to create static, animated, and interactive visualizations in Python. It is widely used in data science, machine learning, and analytics to represent data in an understandable way.

## Uses of Matplotlib
1.	Data Analysis & Exploration – Helps in understanding data patterns and distributions.
2.	Scientific & Engineering Applications – Used in research for plotting graphs of equations.
3.	Machine Learning & AI – Visualizes model performance and comparisons.
4.	Business & Financial Analysis – Helps in presenting reports and dashboards.
5.	Real-time Data Monitoring – Used for tracking trends in various domains.
Install Matplotlib in VS Code:-
Use the code “pip install matplotlib

![image](https://github.com/user-attachments/assets/804606bd-1834-4de8-9f11-6065025cffc0)

Working area of the VS Code write :” import matplotlib.pyplot as plt”
![image](https://github.com/user-attachments/assets/d63e792c-5c0e-4956-9870-b23405101329)

Basic Parameters in Matplotlib
When plotting with Matplotlib, we often adjust certain parameters to control the appearance of the graph. Some important parameters include:
1.	figsize – Controls the size of the figure (e.g., figsize=(10,5))
2.	color – Sets the color of the plot (e.g., color='red')
3.	label – Adds labels to axes or legends (e.g., label='Sales')
4.	linewidth (lw) – Sets the width of the plot lines (e.g., linewidth=2)
5.	linestyle (ls) – Defines the line type (e.g., linestyle='dashed')
6.	marker – Adds markers to points in a plot (e.g., marker='o')
7.	title – Sets the title of the plot (e.g., title='Sales Report')
8.	xlabel, ylabel – Labels the x-axis and y-axis (e.g., xlabel='Months', ylabel='Revenue')
9.	grid – Enables grid lines in the plot (e.g., grid=True)
10.	alpha – Sets the transparency of the plot (e.g., alpha=0.5)


1.Figsize:-
Purpose:
This parameter is used to control the size of the entire figure (the overall plot area). It is particularly useful when you want to make the plot larger or smaller depending on your needs.
Definition:
figsize takes a tuple of (width, height) in inches.
![image](https://github.com/user-attachments/assets/6dac03cd-c0b2-49d8-a4ff-a72ee8e35204) 

![Figure_1](https://github.com/user-attachments/assets/b1a07074-021c-4923-9cc4-c490a7a40942)

2. Color:-
Purpose:
The color parameter is used to set the color of the plot elements (lines, markers, etc.).
![image](https://github.com/user-attachments/assets/25abef06-909a-4aa9-a614-760b901feea7) 
![Figure_2](https://github.com/user-attachments/assets/0824a44b-808d-4453-83e5-a1c062cb2e09)


3.Label :-
Purpose:
The label parameter is used to provide a label for the plot. This label is typically used for the legend, which helps identify multiple data series in the same plot.
![image](https://github.com/user-attachments/assets/3a679107-e4cf-4b56-ac35-601b12f8698f)
![Figure_3](https://github.com/user-attachments/assets/80068122-6f42-4596-8faf-31bde6b92eaa)

 
4.Linewidth (or lw):-
Purpose:
This parameter controls the thickness of the plot lines. A larger value will make the lines thicker and more prominent.
![image](https://github.com/user-attachments/assets/8525b96e-3fef-4dfe-8925-0891ba3b72a9)
![Figure_4](https://github.com/user-attachments/assets/b1a581a0-f72c-44f4-af9e-1d5525309b76)


 

5.Linestyle (or ls):-
Purpose:
The linestyle parameter defines how the plot lines are drawn. You can use different styles, such as solid, dashed, or dotted lines.
![image](https://github.com/user-attachments/assets/30a9d9e1-1143-4c74-adbb-01dc50fb69f7)
![image](https://github.com/user-attachments/assets/adeeecd4-18a4-4c70-9117-d2f14d809628)
![image](https://github.com/user-attachments/assets/2c3c6d46-4bcc-4e0a-87bf-cc8629122066)

![Figure_5](https://github.com/user-attachments/assets/d7301714-f541-4382-b56f-3c8925235af7)
![Figure_6](https://github.com/user-attachments/assets/b00356ad-ff36-43fa-af7f-cb27f9eae60a)
![Figure_7](https://github.com/user-attachments/assets/fd308b1d-2270-4c2b-a831-42f5c4998953)

Here’s a table showing the list of markers available in Matplotlib along with an example of how each marker looks in a plot.
![image](https://github.com/user-attachments/assets/698b7e96-81b5-4f19-bb2f-4733867e7f1a)



6.Marker :-
Purpose:
The marker parameter adds markers to the data points. These markers are symbols that appear at each data point, helping to make individual data points more visible.
'o' for circle
      's' for square
   'd' for diamond
   'x' for cross
   '+' for plus sign

![image](https://github.com/user-attachments/assets/212af9da-bb0d-45a1-9740-248c7af85ac9)
![image](https://github.com/user-attachments/assets/0fe2cbf4-e015-4ae7-b2ca-7a2ee1e48443)
![image](https://github.com/user-attachments/assets/e5ec1e7e-0699-4011-a0e8-186b85219bd6)
![image](https://github.com/user-attachments/assets/8d8b0431-be1b-4e1e-8769-623a41426584)
![image](https://github.com/user-attachments/assets/57ea125a-67e6-437d-9acd-c562a24db623)

![Figure_8](https://github.com/user-attachments/assets/598473d8-3d89-406c-b9c2-6ac52c039a8c)
![Figure_9](https://github.com/user-attachments/assets/e873095a-d7c3-4796-919c-3a9b8d5d5583)
![Figure_10](https://github.com/user-attachments/assets/05b53417-5014-457d-8157-724b5a7c2e24)

![Figure_11](https://github.com/user-attachments/assets/6e3ea3d0-8cc3-42ff-b228-afa4baa8446f)

7. Title
Purpose:
The title parameter is used to set the title of the plot, which typically appears at the top of the figure. This is important for providing context about the plot.
![image](https://github.com/user-attachments/assets/891562e4-6a7e-457e-bb39-5b7fd94f8b49)

![Figure_12](https://github.com/user-attachments/assets/e93730c3-ebaa-4ef6-93aa-c85eeccaa8f1)

 
8.Xlabel and Ylabel
Purpose:
The xlabel and ylabel parameters are used to label the x-axis and y-axis, respectively. These labels help provide context for what each axis represents.
![image](https://github.com/user-attachments/assets/020685d1-fbf5-4bc6-a0f7-414844710794)


![image](https://github.com/user-attachments/assets/c521bbf7-2dc2-4697-a2e4-c8f8e9ec63a5)

 
9. Grid:-
Purpose:
The grid parameter enables or disables the grid lines in the plot. Grid lines can help improve readability, especially in plots with a lot of data points.

Grid lines will be enabled, which can make it easier to read the values and interpret the plot. Use grid(False) to disable grid lines.
![image](https://github.com/user-attachments/assets/b691610d-b68d-4923-99ae-6066ea752b66)
![image](https://github.com/user-attachments/assets/b2a6d1fb-674f-465a-a93f-61fce62c7b15)

![image](https://github.com/user-attachments/assets/1e139d80-dedd-4c4a-896a-a47c08dd337f)

![image](https://github.com/user-attachments/assets/f0543a4f-b144-4d15-bd29-cd005c39ba1d)


  
10.Alpha:-
Purpose:
The alpha parameter controls the transparency of the plot elements. A value of 1 means fully opaque, and 0 means fully transparent.
![image](https://github.com/user-attachments/assets/ef28024b-9c0e-4123-b843-a985fc427df2)

![image](https://github.com/user-attachments/assets/705a5bda-9226-48c6-901a-7f1cc48dc10a)

 

Combining All Parameters
![image](https://github.com/user-attachments/assets/0fabc3cb-d875-4e19-a8f7-248b921bb15a)

![image](https://github.com/user-attachments/assets/83b4a6cf-cd01-484a-bf93-39222b5afde7)

 






##  List of Plots in Matplotlib
* 1.Line Plot (plt.plot())
Purpose:
•	Used for trend analysis over time.
•	Ideal for continuous data (e.g., stock prices, temperature changes).
![image](https://github.com/user-attachments/assets/7f03693d-e256-42da-ade4-83eb1c34313b)
![Image](https://github.com/user-attachments/assets/f23b10c4-5cfa-4b07-90e2-8ba7d83982d4)
 
* 2. Bar Chart (plt.bar())
Purpose:
•	Used to compare categories.
•	Suitable for discrete data (e.g., sales in different months).
![image](https://github.com/user-attachments/assets/737ac259-3b44-4b5d-bedc-f2a13dd371ef)
![Image](https://github.com/user-attachments/assets/dd775530-4234-4b0c-8afb-b23a017016b9)
 

* 3. Histogram (plt.hist())
Purpose:
•	Used for frequency distribution.
•	Ideal for continuous data grouped into bins (e.g., age distribution).
![image](https://github.com/user-attachments/assets/6bd44525-51d2-46fd-a880-b32a64b4f4aa)
![Image](https://github.com/user-attachments/assets/af38e229-b296-449e-9745-97206efc1a7e)
 

* 4. Scatter Plot (plt.scatter())
Purpose:
•	Used to show relationships between two variables.
•	Helpful for correlation analysis (e.g., height vs. weight).
![image](https://github.com/user-attachments/assets/6b7fb5c0-fbdc-4f61-8275-dba121fb4413)
![Image](https://github.com/user-attachments/assets/70fb3807-45cc-44c0-a90e-2ad7d615c1a6)
 

* 5. Pie Chart (plt.pie())
Purpose:
•	Used to show proportions of a whole.
•	Ideal for percentage-based distributions.
![image](https://github.com/user-attachments/assets/3047bceb-a468-4376-9b14-ed80f4b73c01)
![Image](https://github.com/user-attachments/assets/0baac712-8211-4325-ac17-4cc582e2b32a)
 

* 6. Box Plot (plt.boxplot()):-
Purpose:
•	Used to show data spread and outliers.
•	Ideal for statistical analysis (e.g., salary distribution).
![image](https://github.com/user-attachments/assets/437f1fd6-ff57-4260-b56f-65565c6f48ce)
![Image](https://github.com/user-attachments/assets/753a31d1-0348-412a-bf73-e5608999985f)
 
* 7. Area Plot (plt.fill_between())
Purpose:
•	Used for cumulative data representation.
•	Helps to highlight areas under a curve.
![image](https://github.com/user-attachments/assets/154803d1-b4f5-4650-b105-84160399efd8)
![Image](https://github.com/user-attachments/assets/982d1d56-9fb2-4747-836f-13d6a6509e5a)
 

* 8. Stacked Bar Chart:-
Purpose:
•	Used to compare proportions within categories.
![image](https://github.com/user-attachments/assets/5987f348-1aba-4e82-9299-38583f957fa0)
![Image](https://github.com/user-attachments/assets/29095f6f-7a4d-47a5-9cff-3b260e6cede9)

 

* 9. Heatmap (plt.imshow())
Purpose:
•	Used to visualize matrix data as colors.
•	Useful for correlation and patterns in large datasets.
![image](https://github.com/user-attachments/assets/e3582557-d808-4472-9cd8-d06ad86f6222)
![Image](https://github.com/user-attachments/assets/643a9b26-cbc5-44db-9a3d-a18223ba95b9)
 
* 10. 3D Plot (Axes3D)
Purpose:
•	Used for visualizing three-dimensional data.
•	Ideal for scientific and engineering data.
![image](https://github.com/user-attachments/assets/e2c91a6a-7d66-49f9-ab72-63cf1c73d6dc)
![Image](https://github.com/user-attachments/assets/34108e41-a2e8-4d6c-9708-7dd6ca457e2c)
 
 



































