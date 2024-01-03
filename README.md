# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
 Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```python
Program for copying the contents from one file to another file
Developed by:NITHISH MD
Register Number:23009587

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![293366207-98415898-13e3-4682-a2e0-8f7fe4e5cd23](https://github.com/Mrnithishx/copy-file/assets/148201573/2d72fffb-c0ec-4384-a0aa-c99cee46b9ba)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
