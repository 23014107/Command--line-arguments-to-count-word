# Command--line-arguments-to-count-word

NAME:RAMYA.P
REGISTER NUMBER: 212223240137
DEPARTMENT: AIML

## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module to use command line arguments.
### Step 2: 
Create a file pointer and open the file which is passed in command line.
### Step 3: 
Initialize word count as zero.
### Step 4:  
For each line in file, split it into words and find number of the words in every line.
### Step 5: 
Sum the number of words in each line.
### Step 6: 
Display the total words in the file.
3
## PROGRAM:
```
Developed by: RAMYA.P
Register no: 212223240137

import sys
count=0
with open(sys.argv[1],'r') as f1:
     for i in fp:
        words=i.split()
        count+=len(words)
print("word count  in file is",count)
```
### OUTPUT:

![image](https://github.com/23014107/Command--line-arguments-to-count-word/assets/151625620/41275ae7-7889-4ce5-a624-3621f6e0736d)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
