# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.
### Step 2: 
Open the file f2 in append mode.
### Step 3: 
Copy the contents using write() with the for loop.
### Step 4:  
End the program.

## PROGRAM:
```
#Developed By: Gowrisankar.p
#Register No: 212222230041
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
### File1:
![Screenshot (86)](https://github.com/gowrisankarponnusamy/copy-file/assets/119393123/627eb833-b9cf-4880-b6ba-66365ae3ec38)
### File2:
![Screenshot (87)](https://github.com/gowrisankarponnusamy/copy-file/assets/119393123/9b21321f-9ca3-4f3e-b6e0-b0dcb70a1f31)
### File1 copied to File2:
![Screenshot (88)](https://github.com/gowrisankarponnusamy/copy-file/assets/119393123/101fc79f-826f-465d-b1a6-1208afcda655)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
