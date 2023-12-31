# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we want to create a text file.

### Step 2: 
Use for loop to count the number of words in the file.
 
### Step 3: 
Use split() to read the splitted words.We assume that words in a sentance are separted by a space character.


### Step 4: 
The length of the split list should equal the numbers of words in the test file. 

### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

### Step 6: 
End the program.
## PROGRAM:
```
#Program to find the word count
#Developed by: Aaron Rajesh R
#Register Number: 23008897
num=0
with open("sample.txt","r") as f1:
  for i in f1:
    word=i.split()
    num+=len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:
![image](https://github.com/23004205/Word-count/assets/138971114/ae8074bb-45bf-4712-bc98-cd5da1ab4049)


## RESULT:
Thus the program is written to find the word count from a text.
