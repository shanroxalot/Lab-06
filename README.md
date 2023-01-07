# Lab-06: Standard Input/Output Functions and Standard Input/Output Streams

## Name: 

## Honor Code:

I, _______, declare that I have completed this assignment completely and entirely on my own, without any unathorized consultation from others or unathorized access to online websites. I have read the UAB Academic Honor Code and understand that any breach of the UAB Academic Honor Code may result in severe penalties.

Student Signature/Initials: ____________

Date: ____________

## Assignment:

Write a program in C to read the input file *listings.csv* and write two functions, one that will sort the data based on hostname, one on price.

1. Declare a struct called 'Listing' with contains all the attributes found in *listings.csv*.

2. Define a function that will take a line of the CSV file and return a 'Listing' struct with corresponding attribute values.

3. Declare an array of the 'Listing' structs.

4. Open the *listings.csv* file with the *fopen()* function.

5. Loop through each line of the *listings.csv* file. Feel free to use either the *fgets()* function or the *getline()* function.

6. For each line, call the function you defined.

7. Store the result in array of 'Listing' structs.

8. Use the qsort() function to sort the array.

9. Use the *fopen()* to open a file in write mode.

10. Use the *fputs()* function or the *fprintf()* to write the sorted structure array to a file.