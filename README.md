# Delete-Words-from-column-name
While analyzing large datasets, we get common repetitive words in multiple columns. The names become irrelevant to the analysis when comparing, therefore, we try to keep the uniqueness of the column name.

There are multiple ways to approach any problem, this is no different. One of the most common ways people go about this issue is replacing the column name discreetly one by one. Let's say we have a dataset on mobile phones, and the dataset has the first column as Manufacture_name. We can easily replace that with Name or Company. However, if there are multiple columns with Manufacture in it

The code is one way to go about it!

These are the steps to follow

1. Get essential libraries
2. Import the dataset; Here we are assuming a CSV file
3. (Optional) Check the dataset and column names
4. Creating a list of custom words we want to remove
5. Creating a new list for modified column names
6. Modifying the existing column names with new names
7. (Optional) Check the dataset again for updated column names
8. Export dataset for future use; Assuming CSV file

Using this code before analysis will help in finding the uniqueness in column names so all the important and relevant information is available and all the common and unimportant names are removed.
