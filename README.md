# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
##### Step 1:Import the sys module.

##### Step 2:Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

##### Step 3:Read the file using read() method.

##### Step 4:
Use split() method to split the file content into words.

##### Step 5:Use len() to find the total words.

##### Step 6:Run the program to determine the number of words in the file created.
## PROGRAM:
```
Developed by: subishesh
Reg by:23003621

Python program for getting the word count from the contents of a file using command line arguments.
import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:

![image](https://user-images.githubusercontent.com/119393424/215859744-b9533e08-176e-420d-a096-c06ec91340f4.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
