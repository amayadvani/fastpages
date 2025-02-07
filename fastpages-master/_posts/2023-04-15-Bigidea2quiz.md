---
toc: true 
layout: base
description: n/a
author: Amay Advani
title : Big Idea 2 quiz Corrections
---


## Review for Big Idea 2

![]({{site.baseurl}}/images/bigidea2.png)

* I got a 19/25 on this quiz as a result of rushing my answers. 

* Some of the skills assessed in the quiz include filtering and sorting data, counting items in a dataset, and identifying advantages of lossless over lossy compression.

## Corrections

### Q2 Advantage of lossless over lossy compression
1.D
0/1 MC pointIncorrect answer
Which of the following is an advantage of a lossless compression algorithm over a lossy compression algorithm?

A
A lossless compression algorithm can guarantee that compressed information is kept secure, while a lossy compression algorithm cannot.

B
A lossless compression algorithm can guarantee reconstruction of original data, while a lossy compression algorithm cannot.

C
A lossless compression algorithm typically allows for faster transmission speeds than does a lossy compression algorithm.

D
A lossless compression algorithm typically provides a greater reduction in the number of bits stored or transmitted than does a lossy compression algorithm.

Answer A
Incorrect. The ability to keep data secure is not a primary function of a compression algorithm.

### Q6 Analyzing weather photos
5.B
0/1 MC pointIncorrect answer
A group of students take hundreds of digital photos for a science project about weather patterns. Each photo file contains data representing the level of red, green, and blue for each pixel in the photo. The file also contains metadata that describes the date, time, and geographic location where the photo was taken. For which of the following goals would analyzing the metadata be more appropriate than analyzing the data?

Select two answers.

A
Determining the chronological order of the photos

B
Determining the number of clouds in a particular photo

C
Determining whether a photo is suitable for printing in black-and-white

D
Determining whether two photos were taken at the same location on different days

Answer A
Correct. The time and date that a photo is taken is considered metadata about the image. This information can be used to determine the chronological order of the images.

### Q10 Combine data sources
5.B
0/1 MC pointIncorrect answer
Each student at a school has a unique student ID number. A teacher has the following spreadsheets available.

Spreadsheet I contains information on all students at the school. For each entry in this spreadsheet, the student name, the student ID, and the student’s grade point average are included.
Spreadsheet II contains information on only students who play at least one sport. For each entry in this spreadsheet, the student ID and the names of the sports the student plays are included.
Spreadsheet III contains information on only students whose grade point average is greater than 3.5. For each entry in this spreadsheet, the student name and the student ID are included.
Spreadsheet IV contains information on only students who play more than one sport. For each entry in this spreadsheet, the student name and the student ID are included.
The teacher wants to determine whether students who play a sport are more or less likely to have higher grade point averages than students who do not play any sports. Which of the following pairs of spreadsheets can be combined and analyzed to determine the desired information?

A
Spreadsheets I and II

B
Spreadsheets I and IV

C
Spreadsheets II and III

D
Spreadsheets III and IV

Answer C
Incorrect. The desired information cannot be determined with these two spreadsheets because students with grade point averages of 3.5 or less cannot be identified.

### Q16 Bookstore spreadsheet
2.B
0/1 MC pointIncorrect answer
A large spreadsheet contains the following information about the books at a bookstore. A sample portion of the spreadsheet is shown below.

 	
A

Book Title

B

Author

C

Genre

D

Number of

Copies in Stock

E

Cost

(in dollars)

1	Little Women	Louisa May Alcott	Fiction	3	13.95
2	The Secret Adversary	Agatha Christie	Mystery	2	12.95
3	A Study in Scarlet	Arthur Conan Doyle	Mystery	0	8.99
4	The Hound of the Baskervilles	Arthur Conan Doyle	Mystery	1	8.95
5	Les Misérables	Victor Hugo	Fiction	1	12.99
6	Frankenstein	Mary Shelley	Horror	2	11.95
An employee wants to count the number of books that meet all of the following criteria.

Is a mystery book
Costs less than $10.00
Has at least one copy in stock
For a given row in the spreadsheet, suppose genre contains the genre as a string, num contains the number of copies in stock as a number, and cost contains the cost as a number. Which of the following expressions will evaluate to true if the book should be counted and evaluates to false otherwise?

A
(genre = "mystery") AND ((1 ≤ num) AND (cost < 10.00))

B
(genre = "mystery") AND ((1 < num) AND (cost < 10.00))

C
(genre = "mystery") OR ((1 ≤ num) OR (cost < 10.00))

D
(genre = "mystery") OR ((1 < num) OR (cost < 10.00))

Answer B
Incorrect. This expression will not count books that have exactly one copy in stock because it uses the expression (1 < num) instead of (1 ≤ num).

### Q17 Clothing store sales information
5.B
0/1 MC pointIncorrect answer
The owner of a clothing store records the following information for each transaction made at the store during a 7-day period.

The date of the transaction
The method of payment used in the transaction
The number of items purchased in the transaction
The total amount of the transaction, in dollars
Customers can pay for purchases using cash, check, a debit card, or a credit card.

Using only the data collected during the 7-day period, which of the following statements is true?

A
The average amount spent per day during the 7-day period can be determined by sorting the data by the total transaction amount, then adding the 7 greatest amounts, and then dividing the sum by 7.

B
The method of payment that was used in the greatest number of transactions during the 7-day period can be determined by sorting the data by the method of payment, then adding the number of items purchased for each type of payment method, and then finding the maximum sum.

C
The most expensive item purchased on a given date can be determined by searching the data for all items purchased on the given date and then sorting the matching items by item price.

D
The total number of items purchased on a given date can be determined by searching the data for all transactions that occurred on the given date and then adding the number of items purchased for each matching transaction.

Answer B
Incorrect. This information can be determined using the data collected, but not the way described in this option. One way to determine the method of payment that was used in the greatest number of transactions during the 7-day period is to sort the data by the method of payment as described. Instead of adding the number of items purchased for each type of payment, a count of each payment type needs to be computed. If the counts are stored in a new field, then the counts can be sorted to find the method of payment used in the greatest number of transactions.

### Q20 Expression to count restaurants
2.B
0/1 MC pointIncorrect answer
A large spreadsheet contains the following information about local restaurants. A sample portion of the spreadsheet is shown below.

A
Restaurant Name	B
Price Range	C
Number of
Customer Ratings	D
Average
Customer Rating	E
Accepts
Credit Cards
1	Joey Calzone’s Pizzeria	lo	182	3.5	false
2	78th Street Bistro	med	41	4.5	false
3	Seaside Taqueria	med	214	4.5	true
4	Delicious Sub Shop II	lo	202	4.0	false
5	Rustic Farm Tavern	hi	116	4.5	true
6	ABC Downtown Diner	med	0	-1.0	true
In column B, the price range represents the typical cost of a meal, where "lo" indicates under $10, "med" indicates $11 to $30, and "hi" indicates over $30.
In column D, the average customer rating is set to -1.0 for restaurants that have no customer ratings.
A student wants to count the number of restaurants in the spreadsheet whose price range is $30 or less and whose average customer rating is at least 4.0. For a given row in the spreadsheet, suppose prcRange contains the price range as a string and avgRating contains the average customer rating as a decimal number.

Which of the following expressions will evaluate to true if the restaurant should be counted and evaluates to false otherwise?

A
(avgRating ≥ 4.0) AND ((prcRange = "lo") AND (prcRange = "med"))

B
(avgRating ≥ 4.0) AND ((prcRange = "lo") OR (prcRange = "med"))

C
(avgRating ≥ 4.0) OR ((prcRange = "lo") AND (prcRange = "med"))

D
(avgRating ≥ 4.0) OR ((prcRange = "lo") OR (prcRange = "med"))

Answer D
Incorrect. This expression will evaluate to true for restaurants with the correct price range or with the correct customer rating. The intent is for the expression to evaluate to true only for restaurants with the correct price range and the correct customer rating.



