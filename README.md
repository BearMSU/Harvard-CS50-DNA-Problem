# Harvard-CS50-DNA-Problem

This is Harvard's CS50x Problem Set 6: DNA done in Python. The program takes command line inputs to open a CSV file and a text file. The CSV files are databases of people (fake) and the text files are DNA sequences (also fake). The program itself compares the DNA sequence from the text file to the people in the CSV file.

If there is a match, the program outputs the person the DNA sequence is a match to. If there is no match, the program prints out "No match".

Example:

In the command line you would type: python dna.py databases/small.csv sequences/1.txt
Your output would be: Bob

In the command line you would type: python dna.py databases/small.csv sequences/2.txt
Your output would be: No match

In the command line you would type: python dna.py databases/large.csv sequences/8.txt
Your output would be: Ginny
