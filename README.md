# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file form which we need to copy the text.
Again using the with keyword to open the empty file.
### Step 2: 
Using keyword "with" to open the requied file. 
### Step 3: 
Again using the with keyword to open the empty file.
### Step 4:  
The empty file is open by using 'W' which is used to write only.
### Step 5: 
The four function is used to take each line from the main file.
### Step 6: 
The four function is used to take each line from the main file.
## PROGRAM:
```
#Developed by: PRADEEP.S
#Reference no: 22009034
with open('file.txt','r') as f1:
    with open('file2.txt','a') as f2:
        for line in f1:
            f2.write(line)
 ```
### OUTPUT:
![cp1](https://user-images.githubusercontent.com/120539823/214834580-67338ddf-3352-4d4e-962b-a385888dc19b.png)
![cp2](https://user-images.githubusercontent.com/120539823/214834654-09ee2f45-b02b-462a-84da-84e59f5422b9.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
