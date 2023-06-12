# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:Import sys module.
Step 2: Open the file with sys.argv[1].
Step 3: Use the for loop to select the content in file.
Step 4:Use split function to to separate the file content into words or strings.
Step 5: Count the length of the words using len.
Step 6:Count the length of the words using len.

## PROGRAM:
```
'''
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: MURALI .S
RegisterNumber:212222230088
'''
import sys
count=0
fp=open(sys.argv[1],'r')
for line in fp:
    list1=line.split()
    count+=len(list1)
print("no of words in a file",count)
```
### OUTPUT:
![5B](https://github.com/MURALI22008445/command-line-arguments-to-count-word/assets/119643767/4a58b0f5-7a39-4442-95ce-23eb98843fda)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
