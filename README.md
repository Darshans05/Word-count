# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First, crate a file in txt mode.

### Step 2: 
next Decleare number of words is 0
 
### Step 3: 
Give range for i
### Step 4:  
Then nxt split the words
### Step 5: 
count the number of words
### Step 6: 
putting print statement for getting output
## PROGRAM:
```python
'''
Program to count the words in the file
developed by: DARSHAN S 
Reg no: 212222100010
'''
fname=input("enter the file name:")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print('Number of words: ',num_words)
```


### OUTPUT:
![word count](https://github.com/Darshans05/Word-count/assets/115534676/1414aeea-db19-4aef-878a-f5fc6d850f2e)



## RESULT:
Thus the program is written to find the word count from a text.
