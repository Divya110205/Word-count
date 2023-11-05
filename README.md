# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Open then required file by using the function"with"

### Step 2:

Using split function to split the words.

### Step 3:

Finding the length of the words by using len() function.

### Step 4:

Calling the function and printing the number of words.

## PROGRAM:
```
# Ex5a Word count
# Program Developed By: DIVYA.A
# Register Number: 212222230034
fname=input('Enter file name: ')
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print('Number of words: ',num_words)
```
## FILE:
![Exp 5a(1)](https://github.com/Divya110205/Word-count/assets/119404855/85098f3a-9c37-48ea-8c15-6a0d0e8c137a)

## OUTPUT:
![Exp 5a(2)](https://github.com/Divya110205/Word-count/assets/119404855/8dc736d6-2528-4b6e-884b-17d82da1db59)

## RESULT:
Thus the program is written to find the word count from a text.
