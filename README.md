# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a file with .txt file extension
### Step 2: 
 add some text in that file
### Step 3: 
create a python file
### Step 4:  
write a code to count the number of words in that file
### Step 5: 
run the program
### Step 6: 
display the output
## PROGRAM:
```
def program():
    count=0
    with open("Files.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Ttotal number of words:",count)
program()
```
### OUTPUT:

![Screenshot (23)](https://github.com/Narendran-sec/Word-count/assets/147473131/3acac566-3e06-4103-864c-231081f8b4ad)

![Screenshot (22)](https://github.com/Narendran-sec/Word-count/assets/147473131/7713dc48-e480-4759-8c74-01387f06da1f)



## RESULT:
Thus the program is written to find the word count from a text.
