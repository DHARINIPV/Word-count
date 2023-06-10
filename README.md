# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:

Create a text file add sentence to it.

### Step 2: 

Using open() open the .txt file in read mode in python compiler. 

### Step 3: 

Assign a variable for value zero.

### Step 4:  

Using the for loop assign the df then use variable to split the content.

### Step 5: 

Iterate in nested loop to increment the variable.

### Step 6: 

Print the variable.

## PROGRAM:

Python program to count the words in file

Programmed By: Dharini PV

Ref. No. : 212222240024
```
fname=input("Enter the file name:")

num_words=0

with open(fname,'r')as f:
    
    for line in f:
        
        words=line.split()
        
        num_words+=len(words)

print('Number of words: ',num_words)
```
### OUTPUT:

![Screenshot 2023-06-10 195242](https://github.com/DHARINIPV/Word-count/assets/119400845/c5872df2-adae-4c4b-9d9a-97c264c15ca9)

![Screenshot 2023-06-10 195253](https://github.com/DHARINIPV/Word-count/assets/119400845/e9a31af2-99b8-4cde-b8c8-9b250446fc7f)

## RESULT:
Thus the program is written to find the word count from a text.
