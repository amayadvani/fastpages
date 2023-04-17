---
toc: true 
layout: base
description: n/a
title : MCQ 4 Test Correction
---

![]({{site.baseurl}}/images/mcq4.png)

## Q11 Collections of books to be combined
2.B
0/1 MC pointIncorrect answer
Two lists, list1 and list2, contain the names of books found in two different collections. A librarian wants to create newList, which will contain the names of all books found in either list, in alphabetical order, with duplicate entries removed.


For example, if list1 contains

["Macbeth", "Frankenstein", "Jane Eyre"]

and list2 contains

["Frankenstein", "Dracula", "Macbeth", "Hamlet"],

then newList will contain

["Dracula", "Frankenstein", "Hamlet", "Jane Eyre", "Macbeth"].


The following procedures are available to create newList.

A table is shown with two columns, Procedure on the left and Explanation on the right. The first row reads Sort open parentheses list close parentheses, and Sorts list in alphabetical order and returns the resulting list. The second row reads Combine open parentheses list1, list2 close parentheses, and Creates a new list consisting of the entries from list1 followed by the entries from list2. The resulting list is returned. The third row reads RemoveDuplicates open parentheses list close parentheses, and Iterates through list. If any two or more entries have the same value, the duplicate entries are removed so that any entry appears at most once. The resulting list is returned.

Which of the following code segments will correctly create newList ?

A
newList ← Combine (list1, list2)

newList ← Sort (newList)

newList ← RemoveDuplicates (newList)

B
list1 ← Sort (list1)

list2 ← Sort (list2)

newList ← Combine (list1, list2)

newList ← RemoveDuplicates (newList)

C
list1 ← RemoveDuplicates (list1)

list2 ← RemoveDuplicates (list2)

newList ← Combine (list1, list2)

newList ← Sort (newList)

D
list1 ← RemoveDuplicates (list1)

list1 ← Sort (list1)

list2 ← RemoveDuplicates (list2)

list2 ← Sort (list2)

newList ← Combine (list1, list2)

Answer B
This option is incorrect. If each list is sorted separately and then combined, the combined list will not necessarily be sorted.

## Q24 The table below shows the time a computer syste...
5.D
0/1 MC pointIncorrect answer
The table below shows the time a computer system takes to complete a specified task on the customer data of different-sized companies.

The figure shows a table with 4 columns and 5 rows. The top row contains the column labels, from left to right; column 1, Task; column 2, Small Company (approximately 100 customers); column 3, Medium Company (approximately 1,000 customers); column 4, Large Company (approximately 10,000 customers). From top to bottom, the data is as follows: Row 2; Task, Backing up data, Small Company, 2 hours, Medium Company, 20 hours, Large Company, 200 hours. Row 3; Task, Deleting entries from data, Small Company, 100 hours, Medium Company, 200 hours, Large Company, 300 hours. Row 4; Task, Searching through data, Small Company, 250 hours, Medium Company, 300 hours, Large Company, 350 hours. Row 5; Task, Sorting data, Small Company, 0.01 hours, Medium Company, 1 hour, Large Company, 100 hours.

Based on the information in the table, which of the following tasks is likely to take the longest amount of time when scaled up for a very large company of approximately 100,000 customers?

A
Backing up data

B
Deleting entries from data

C
Searching through data

D
Sorting data

## Q26 Data compression and its use
1.D
0/1 MC pointIncorrect answer
Which of the following is a true statement about data compression?

A
Data compression is only useful for files being transmitted over the Internet.

B
Regardless of the compression technique used, once a data file is compressed, it cannot be restored to its original state.

C
Sending a compressed version of a file ensures that the contents of the file cannot be intercepted by an unauthorized user.

D
There are trade-offs involved in choosing a compression technique for storing and transmitting data.

## Q36 Algorithm that would most benefit from a heuristic
1.D
0/1 MC pointIncorrect answer
For which of the following situations would it be best to use a heuristic in order to find a solution that runs in a reasonable amount of time?

A
Appending a value to a list of n
 elements, which requires no list elements be examined.

B
Finding the fastest route that visits every location among n
 locations, which requires n!
 possible routes be examined.

C
Performing a binary search for a score in a sorted list of n
 scores, which requires that fewer than n
 scores be examined.

D
Performing a linear search for a name in an unsorted database of n
 people, which requires that up to n
 entries be examined.

Answer A
Incorrect. This algorithm requires just one step, so it runs in a reasonable amount of time. Therefore, a heuristic is not appropriate.

## Q39 Displaying random values in a loop
4.B
0/1 MC pointIncorrect answer
Consider the following code segment.

The figure presents two blocks of code that consist of 5 total lines. Throughout the blocks of code there are nested blocks of code, as follows. Line 1: [begin block] i ← 1 [end block] [begin block] Line 2: REPEAT UNTIL [begin block] i greater than 4 [end block] [begin block] Line 3: [begin block] rand ← RANDOM [begin block] 1, i [end block] [end block] Line 4: [begin block] DISPLAY [begin block] rand [end block] [end block] Line 5: [begin block] i ← i + 1 [end block] [end block] [end block]
Which of the following CANNOT be displayed as a result of executing the code segment?

A
1 1 1 1

B
1 2 3 2

C
1 2 3 4

D
1 3 2 4

Answer C
Incorrect. The first number displayed must be 1. The second number displayed could be 1 or 2. The third number displayed could be 1, 2, or 3. The last number displayed could be 1, 2, 3, or 4. So 1 2 3 4 is a possible output.

## Q49 Traverse list to compare quiz scores
2.B
0/1 MC pointIncorrect answer
A teacher stores the most recent quiz scores for her class in the list scores. The first element in the list holds the maximum possible number of points that can be awarded on the quiz, and each remaining element holds one student’s quiz score. Assume that scores contains at least two elements. Which of the following code segments will set the variable found to true if at least one student scored the maximum possible number of points on the quiz and will set found to false otherwise?

A
The figure presents four blocks of code that consist of 7 lines. Throughout the blocks of code there are nested blocks of code, as follows. Line 1: [begin block] len ← LENGTH [begin block] scores [end block] - 1 [end block] Line 2: [begin block] found ← false [end block] Line 3: [begin block] index ← 2 [end block] [begin block] Line 4: REPEAT len TIMES [begin block] [begin block] Line 5: IF [begin block] scores [begin block] index [end block] = scores [begin block] 1 [end block] [end block] [begin block] Line 6: [begin block] found ← true [end block] [end block] [end block] Line 7: [begin block] index ← index + 1 [end block] [end block] [end block]

B
The figure presents four blocks of code that consist of 7 lines. Throughout the blocks of code there are nested blocks of code, as follows. Line 1: [begin block] len ← LENGTH [begin block] scores [end block] [end block] Line 2: [begin block] found ← false [end block] Line 3: [begin block] index ← 1 [end block] [begin block] Line 4: REPEAT len TIMES [begin block] [begin block] Line 5: IF [begin block] scores [begin block] index [end block] = scores [begin block] 1 [end block] [end block] [begin block] Line 6: [begin block] found ← true [end block] [end block] [end block] Line 7: [begin block] index ← index + 1 [end block] [end block] [end block]

C
The figure presents four blocks of code that consist of 7 lines. Throughout the blocks of code there are nested blocks of code, as follows. Line 1: [begin block] len ← LENGTH [begin block] scores [end block] [end block] Line 2: [begin block] found ← false [end block] Line 3: [begin block] index ← 2 [end block] [begin block] Line 4: REPEAT UNTIL [begin block] index greater than or equal to len [end block] [begin block] [begin block] Line 5: IF [begin block] scores [begin block] index [end block] = scores [begin block] 1 [end block] [end block] [begin block] Line 6: [begin block] found ← true [end block] [end block] [end block] Line 7: [begin block] index ← index + 1 [end block] [end block] [end block]

D
The figure presents two blocks of code that consist of 4 lines. Throughout the blocks of code there are nested blocks of code, as follows. Line 1: [begin block] found ← false [end block] [begin block] Line 2: FOR EACH value IN scores [begin block] [begin block] Line 3: IF [begin block] value = scores [begin block] 1 [end block] [end block] [begin block] Line 4: [begin block] found ← true [end block] [end block] [end block] [end block] [end block]

Answer C
Incorrect. This code segment traverses the list beginning with the second element, so it is correctly comparing only the student scores to the maximum possible score. However, the code segment will fail to check the last element in the list. When index is equal to the length of the list, the loop will terminate without comparing the last student score in the list to the maximum possible score.


