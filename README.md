# ZombieCatcher

A Java command-line program that identifies visitors who need to be quarantined based on overlapping time periods with a known zombie presence.

---

## Description

This program helps track potential exposure to a zombie outbreak by checking if visitors were on-site during an infection period. It supports manual input of visitor times and can also read visitor logs from files.

---

## How to Use

1. Compile the program by running:

javac ZombieCatcher.java

2. Run the program:

- For manual input, run:

java ZombieCatcher

- To read visitor data from one or more files, run:

java ZombieCatcher file1.txt file2.txt

---

## Example

Manual input example:

Enter the start time:  
5  
Enter the end time:  
7  
Enter the number of visitors:  
2  
Enter the visitor's name:  
Sulaimaan  
Enter the arrival time:  
4  
Enter the departure time:  
8  
Sulaimaan needs to be quarantined.  
Enter the visitor's name:  
Dmani  
Enter the arrival time:  
8  
Enter the departure time:  
9  
Dmani does not need to be quarantined.  
Number of potential zombies: 1

---

## License

This project is open-source under the MIT License. See the LICENSE file for details.
