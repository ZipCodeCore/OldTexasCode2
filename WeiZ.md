The code for SimpleWordCounter.java works by importing the file using File class. Then initiating the scanner to read 
the file. Following which the program creates an array to store word and word count. Within the loop, the code scans for
words already in the array to increase the word count associated with the word. Otherwise if the word is not
already in the list, the program adds it the array and set count to 1. After the while loop finish the entire file,
it prints out the array line by line to display the word and its count. Lastly, they have a catch exception, incase the
file cannot be read.