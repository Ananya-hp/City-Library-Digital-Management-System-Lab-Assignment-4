# City-Library-Digital-Management-System-Lab-Assignment-4

This project is developed as part of Java Programming Assignment 4.
It implements a complete digital library management system using File Handling and the Java Collections Framework.
The system supports:

1. Adding books and members

2. Issuing and returning books

3. Searching and sorting book records

4. Saving and loading data using text files

5. Using Maps, Lists, Sets, Comparable & Comparator

📌**Key Features**

**1.Add Book**

Stores Book ID, Title, Author, Category

Default status: Not Issued

Saved into books.txt

**2.Add Member**

Stores Member ID, Name, Email

Maintains issued books list

Saved into members.txt

**3.Issue Book**

Book must exist and must not be already issued

Member must exist

Updates:

isIssued = true

Adds book ID to member’s issuedBooks list

Saves updated data to file

**4.Return Book**

Marks book as returned

Removes book ID from member’s issued list

Saves updated data

**5.Search Books**

Search using title, author, or category
(Substring search, case-insensitive)

**6.Sort Books**

Sort by Title (Comparable)

Sort by Author (Comparator)

**🛠️Tools & Technologies Used**

- Java (JDK 8+)

- Object-Oriented Programming

- Java File Handling

- FileWriter, FileReader

- BufferedWriter, BufferedReader

- Java Collection Framework

- ArrayList

- Collections utility methods

**📝Conclusion**

This project demonstrates strong implementation of:

- File Handling for persistent data

- Java Collections for efficient storage and retrieval

- OOP principles for structuring a real-world system

- Searching and sorting using Java utilities

It is a complete, functional, and well-structured digital library management system.
