# DataWeave---Task

## Language used - Python 

## Pre-requisites
Both the json files had been loaded as dictionaries.

## Question - 1 - Number of URLH which are overlapping (Common) in two files.
1. The urlh's of two files are stored in two set.
2. 'Intersection' is used between those sets and length is shown.

## Question - 3 - Number of Unique categories in both files.
1. The categories in two files are stored in two set seperately.
2. The unique values is found.
3. Then length of unique values is found.

## Question - 4 - Display List of categories which is not overlapping (Common) from two given files.
1. Using set differnce method, the symmetric difference has been found.
2. if there are null difference, then there will be no output in the 'set()'.

## Question - 6 - Generate a new file where mrp is normalized. If there is a 0 or a non-float value or the key doesn't exist, make it "NA".
1. The mrp in each dataset is loaded in two different lists.
2. The condition is passed such that 0 or non-float value must be 'NA".
3. A package 'xlsxwriter' is imported to make a new xlsx file.
4. The normalized mrp is stored seperately in two columns as 'MRP OF TODAY.JSON' and 'MRP OF YESTERDAY OF JSON' respectively and saved.

## Question - 7 - Display the title and price of 10 items having least price.
1. Dictionaries has been declared and the key has been set.
2. The conversion of non-type to string has been done.
3. The title and the price is sorted and the sliced to 10 items with least price order.

## Question - 8 - Display the top 5 subcategory having highest items.
1. Similarly, the subcategories and pack size has been used and sorted in reverse.
2. Then the top 5 items corresponding to subcategories has been listed.

## Question - 9 - Display stats of how many items have failed status (http_status other than 200 is to be considered as failure).
1. The http_status of both files has been stored in a single list.
2. Then, the values in list is parsed into a dictionary.
3. Inorder to find the failure, a constraint has been set and looped through dictionary to obtain the http_status.

# OUTPUT:
![OUTPUT](https://user-images.githubusercontent.com/59074144/124818268-71a33600-df88-11eb-986f-ee727201316a.png)
