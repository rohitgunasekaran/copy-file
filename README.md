# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Create a text1.txt with some content in it

### Step 2: : Open the text1.txt file in read mode
 
### Step 3: Create a copy.txt file using write mode

### Step 4:  Copy the content of text1.txt file to copy.txt using write function

### Step 5: print the content

### Step 6:  End the program

## PROGRAM:
       #Program for copying the contents from one file to another file

        #Developed by: Rohit g

        #RegisterNumber: 212222240083

     with open("text1.txt",'r') as fp:
     
     msg1=fp.read()
     
     
     with open("copytxt",'w') as fp1:
     
     fp1.write(msg1)

### OUTPUT:
![image](https://github.com/rohitgunasekaran/copy-file/assets/119404546/0aa4a6fc-24dd-453b-a7eb-a2dfe087c0b8)
![image](https://github.com/rohitgunasekaran/copy-file/assets/119404546/c8539f3b-ae32-4cae-a6d4-30411d16e302)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
