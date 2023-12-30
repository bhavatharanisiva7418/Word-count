# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read modeand handle it in test mood.
### Step 2: 
 Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the test file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
```
## Developed by: BHAVATHARANI S
## Reference Number: 212223230032
num_word=0
with open ("sample.txt",'r') as f:
 for i in f:
 word=i.split()
 num_word+=len(word)
print("number of words ={}".format(num_word))
```
### OUTPUT:
![output](./wordcountoutput.png)


## RESULT:
Thus the program is written to find the word count from a text.
