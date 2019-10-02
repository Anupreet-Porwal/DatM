## Homework 1 

This file contains solutions to the Chipotle Analysis of Dat8. 

The file **chipotle.tsv** contains 5 columns with names as order_id, quantity, description, choice_description and the price of the product. The rows represent different customer orders. There appears to be 1834 orders in total. There are 4623 lines in total. 


Chicken Burritos are more popular and usually found with Black beans. There are 13 files available with .csv or .tsv extension in DAT8 directory and subdirectory. Dictionary word is found in 84 lines in total in DAT8 folder. 

```
head chipotle.tsv 
tail chipotle.tsv

wc -l chipotle.tsv

grep -i "steak burrito" chipotle.csv | wc -l 
grep -i "chicken burrito" chipotle.csv | wc -l 

grep -i "chicken burrito" chipotle.csv | grep -i "black beans" | wc -l
grep -i "chicken burrito" chipotle.csv | grep -i "pinto beans" | wc -l

cd ..
find . -name *.?sv

grep -ir "dictionary" . | wc -l

```