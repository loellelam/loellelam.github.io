---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Bank Database"
date: 2022
published: true
labels:
  - C
  - C++
  - Makefile
summary: "A mock bank database that provides basic functionality including adding, printing, finding, and deleting records."
---

The "Bank Database" project serves as my final project in my Spring 2022 ICS 212 course. The primary objective behind this project was to consolidate and apply the knowledge and skills acquired throughout the entire semester, culminating in the development of a comprehensive final project.

The program serves as a user interface for managing a bank database. It allows users to interact with a linked list data structure, offering menu options to add new records, print all existing records, find records by account number, delete records by account number, and exit the program. The user interface is text-based and guides users through each operation, such as entering account numbers, names, and multi-line addresses when adding new records. The program handles input validation to ensure data integrity and provides appropriate feedback to users.

Here is a look at the user interface:

```

Welcome to Bank Database Application!
Successfully retrieved records

Choose a menu option from the list below by typing its name or a subset of its name.
add: Add a new record in the database
printall: Print all records in the database
find: Find record with a specified account #
delete: Delete existing record from the database using the account # as a key
quit: Quit the program

```

Let's type `p` to print all current records:

```
p
Record list:
900
Carl
1743 Baker Street

1000
Mr. Harrison
123 Main St
Honolulu, HI 96822

1000
Jackie Smith
Etheria Cloud #500
Skyward Realm
```

Type `f` and enter 1000 to find all records with an account number of 1000:

```
f
Enter account number: 1000
1000
Mr. Harrison
123 Main St
Honolulu, HI 96822

1000
Jackie Smith
Etheria Cloud #500
Skyward Realm
```

To view the full project, visit my [GitHub](https://github.com/loellelam/Bank-Database).
