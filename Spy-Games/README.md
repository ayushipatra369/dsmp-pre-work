## Project Overview

 Encrypted/Secret message was received from intel. Those messages have multiple text files that need to be read and have certain operations performed to get the final message. Helped to decipher a message for time-being.


## Learnings from the project

 Lots of Python function, such as 
 
    1. open(file_name,mode) , to open a file in read mode 
    2. write() , to append into the existing file 
    3. close() , to close the file 
    4. split() , split a message into list of words 
    5. lambda function,  one important learning for ME, lambda function can be used within user-defined function. How cool is that!! 
    6. filter() , to filter the value of lambda function from a list (in this particular project)
    
Learnt to comapre two files by selecting the portion we need (through if statement), after converting the message in the file into list. 


## Approach taken to solve the problem


###Message Reading
Created a function to read files, where the path of the file was stored in a variable file_path. 

###Message Fusion
Extracted one part the secret message from different two files 

###Message Substitution 
Substitute the message of the file for a secret message. Basically, decrypted the secret message. 

###Message Comparison
Another way to extract message by comparing two files and selecting the portion which is important

###Message Filter
Filter the word whose length is even in a message 

###Message Writing 
Combined all the message extracted in the above steps and wrote them into a single file 


## Challenges faced

 One challenge was to figure out which built in functions to use for a particular operation. 

For example, comparing or finding difference between two list. It can be done through set function but set in python are unordered which makes the output inconsistent. I googled and found out different methods to comapre two list. 


