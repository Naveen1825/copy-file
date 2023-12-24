# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output
## PROGRAM:
```
with open("trty","r") as f1:
    with open("copy.txt","w") as f2:
        line=f1.read()
        f2.write(line)
```
### OUTPUT:
### Program
<img width="649" alt="292431646-21ab9e46-1fff-4ace-b4e1-c4680576e0b7" src="https://github.com/Naveen1825/copy-file/assets/138969868/254ee635-29a2-4de5-a169-1d2823e1ea43"><br>
### Original file(trty.txt)
<img width="960" alt="292432529-dd6fb748-4a8f-417c-b459-90401d463d6b" src="https://github.com/Naveen1825/copy-file/assets/138969868/3c9b4dcc-b280-4da5-ada6-cf36bb29f8ab"><br>
### Copied file(copy.txt)
<img width="960" alt="292432629-ce384654-101c-4e8c-85bd-d0f16099bb43" src="https://github.com/Naveen1825/copy-file/assets/138969868/3cd618ee-ba63-4dff-8f39-b99764111426"><br>
### terminal
<img width="901" alt="292432742-4f6af7c5-18c1-4638-b29d-4eddc12900ef" src="https://github.com/Naveen1825/copy-file/assets/138969868/e1ed03e4-174d-464d-b09f-ffb79f610764"><br>

## RESULT:
Thus the program is written to copy the contents from one file to another file.
