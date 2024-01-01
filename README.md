# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2:
Read the file and store in a variable.

### Step 3:
Now create a new file in which we want to paste the content using write access mode.

### Step 4:
Use write function to copy the read file that has been stored in the variable.

### Step 5:
The content in the original file will be copied in the new file.

### Step 6:
End the program.

## PROGRAM:
```
'''
Developed by: GOKHULRAJ V
RegisterNumber: 212223230064
'''
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### OUTPUT:

![image](https://github.com/Gokhulraj2005/copy-file/assets/138849253/b8abe3a9-3476-4b1a-a89a-fb648c9dbed0)
![image](https://github.com/Gokhulraj2005/copy-file/assets/138849253/549d93d9-b001-4e88-b26d-0d20f8bc6801)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
