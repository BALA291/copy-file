# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a f1.txt with some content in it

### Step 2: 
 Open the f1.txt file in read mode

### Step 3: 
Create a f2.txt file using write mode

### Step 4:  
Copy the content of f1.txt file to f2.txt using write function


## PROGRAM:
```
#Developed By: BALAMURUGAN B
#Register No: 212222230016
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)

```

### OUTPUT:
![5c](https://github.com/BALA291/copy-file/assets/120717501/8ba47254-bb02-4d62-ae56-958468ffcfd9)



![5cfi](https://github.com/BALA291/copy-file/assets/120717501/d5250c40-3cb6-4d6e-9b19-814ad5d79a84)



![5cfii](https://github.com/BALA291/copy-file/assets/120717501/55aaf5ef-b5ec-4ddd-8263-b0d6f5c791f4)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
