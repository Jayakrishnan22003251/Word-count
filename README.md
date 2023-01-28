# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
  Decleare number of words is 0
### Step 2: 
  Open it with txt file
### Step 3: 
  Give range for i
### Step 4:  
  Then nxt split the words
### Step 5: 
  count the number of words
### Step 6: 
  Giving print statement for getting output
## PROGRAM:
```
#Developed by : JAYAKRISHNAN L B L
#Reg no : 22003251
num_words = 0
with open('text.txt','r') as file1:
  for i in file1:
    word = i.split()
    num_words += len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/120232371/215267953-0e359f29-6b49-4427-b83c-2a671923e8e6.png)


## RESULT:
Thus the program is written to find the word count from a text.
