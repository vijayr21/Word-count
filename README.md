# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:To write a python program for getting the word count from a text file



### Step 2: Open the required file by using the function "with".


 
### Step 3: Then use the laptop to assign the i value in the file.


### Step 4:Using split function to spilt the words  


### Step 5:Finding the given length of the words by using len() fuction. 


### Step 6: Calling the function and Printing the number of words


## PROGRAM:
```
## Developed by: Charumathi R
## Reference Number: 22006878
num_word=0
with open ("sample.txt",'r') as f:
 for i in f:
 word=i.split()
 num_word+=len(word)
print("number of words ={}".format(num_word))
```

### OUTPUT:
![python 5 1](https://github.com/vijayr21/Word-count/assets/149347607/280fb6a9-5abb-44ee-9c66-ea99cb2decf0)
![python 5](https://github.com/vijayr21/Word-count/assets/149347607/59a84e88-7a62-406d-b0ba-242437a2f4c2)





## RESULT:
Thus the program is written to find the word count from a text.
