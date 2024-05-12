# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file with .txt file extension

#### Step 2:
Add some text in that file

### Step 3:
Create a python file

### Step 4:
Write the code to count the number of words in that file

### Step 5:
Run the program

### Step 6:
Display the output

## PROGRAM:
```py
#Developed by: SANTHOSH G
#Register Number: 212223240152

num=0

with open("Untitled.txt","r") as f1:

    for i in f1:

        word=i.split()

        num += len(word)

print("The number of words are in the file is ",num)
```

### OUTPUT:

![Screenshot 2024-05-12 150753](https://github.com/GSanthosh007/Word-Count/assets/147527586/bed91df4-93c1-452d-8185-e160b057653e)


## RESULT:
Thus the program is written to find the word count from a text.
