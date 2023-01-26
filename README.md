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
### OUTPUT:
![cp1](https://user-images.githubusercontent.com/120539823/214834126-c30dcd8c-6a42-49ef-a384-691808c6fb38.png)
![cp2](https://user-images.githubusercontent.com/120539823/214834131-cc1b7c99-c9ed-4319-b7dd-200a24a63d3c.png)

![wordcount2](https://user-images.githubusercontent.com/120539823/214834133-f7fff0ef-1e98-4ae4-a336-57b7293bc807.png)
![cp2](https://user-images.githubusercontent.com/120539823/214834166-f72bbbab-a776-440b-9972-4582c8257422.png)
![wordcount2](https://user-images.githubusercontent.com/120539823/214834169-faae48c7-1074-4623-9b4a-12cb2e088b22.png)
![cp1](https://user-images.githubusercontent.com/120539823/214834171-bb7b592f-2423-4a22-b221-86ee3ab3a7ae.png)


```
## RESULT:
Thus the program is written to copy the contents from one file to another file.
