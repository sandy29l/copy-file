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
### Step 5: 
print the content
### Step 6: 
end the program!
## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: Santhosh L
RegisterNumber: 212222100046

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)

```
### OUTPUT:
![v1](https://github.com/sandy29l/copy-file/assets/123359969/13cedf50-3208-41b1-91e8-fa0fefc881c6)

![v2](https://github.com/sandy29l/copy-file/assets/123359969/821cad5a-efe4-4071-94d3-52a0589cd613)

![v3](https://github.com/sandy29l/copy-file/assets/123359969/7fb145ad-7b4f-47a8-ad4d-9a36da778f87)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
