# Lab-1_202001268

## [Q.1] - LIBRARY INFORMATION SYSTEM[LIS]
###      Functional requirements
* A system should present all the necessary details about the book.
* The system should ask users for their username and password when they want to issue a book. The system checks whether submitted data is accurate, such as whether a password was properly entered or whether a username was entered.
* A system should allow users to look for books in the library using criteria like the title, author, release date, etc. in accordance with their needs.
* The system assigns a unique identifying number to each items. It should also assign each member a special identification number.
* Users should be able to use the system to reserve a specific item they desire from anywhere by providing their identification number.
* Only if the user is a member of the system should the LIS system enable the user to borrow a book or return it if it has already been borrowed. Once a librarian confirms a user's request to borrow a book, the user is then able to borrow it.
* If a book has already been borrowed by another user, the system should notify the user that the book has already been borrowed by others rather than giving the user the option to borrow it.
* The system should provide the user with the list of books they now have out to borrow, books they have previously borrowed, the dates they were borrowed and returned, and additional information they want.
* The librarian should be able to add new records to the database when a new book is purchased and remove records whenever a book is taken off the shelf using a system.
* When the books are returned, the system should calculate the fee for the overdue books and notify the user and librarian of the overdue books.
* The system should offer a better search option for the books that are currently in stock.

### Non-functional requirements
* Scalability - System must be usable forextended numbers of users if required and system shouldn't fail and should function consistently.
* Security – To access the system, a user must enter a username and password. Additionally, it needs to confirm that it functions on the university LAN.
System should be reliable and accessible throughout the entire time when the library is open. 
* Maintability - The system should be created in a way that makes changing data as easy as is practical. The current system should continue to work properly even after changes are made. In the event that further features must be introduced, the system need to operate well.
* Realibility - System should be reliable and accessible throughout the entire time the library is open. The system shouldn't have any failures at this specific time.
* Portability - Access to the database is possible on any platform other than the it was made.
* Performance - Requests should receive a response from the system in two to three seconds.
* Flexibility - The system should make sure that users may quickly obtain relevant data. The user interface should be understandble to everyone. It might be much simpler if a variety of languages are available.
