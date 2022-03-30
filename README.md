# Libby App Data Modeling
Bena Huang
<br>November 26, 2020 
<br>Project 1
## Business Case
Libby is a free application available on app stores that allows library card holders to conveniently borrow electronic books, also known as e-books, and audiobooks from their smartphones and remove the need to go to physical library locations to borrow books. Users who sign up with the app will have to register their library cards in order to access their local library’s inventory of books. Some users who hold library cards to multiple libraries can register multiple library cards.
<br><br>The app categorizes the library’s inventory by genre but also by collections they feel users would like, such as Just Added, New Books, and Lucky Day Collection which are ebooks that have no waiting list and can be borrowed right away. Users are also allowed to update their preferences by: format, language, audience, ebook device compatibility, and availability, which can help further customize the books that Libby suggests to users.
<br><br>If a user wants to borrow an ebook that has a waiting list, they’re able to place a hold on the book, which holds their place on the waiting list. Once their turn is reached on the waiting list, the book is moved to the user’s Loans section. Users are allowed to borrow the book for up to 21 days. If the user needs more time to finish the book, they’re able to renew the book but only if there are no other users on the waiting list. Local library branches set limits for how many holds and loans users are able to have at a certain time. Aside from borrowing books, users are also able to personal lists of books using Tags.
<br><br>The main entities involved in this app are: Users, Libraries, Library Cards, and Books. The following diagram describes the entities and their respective details, as well as the relationships between these entities. User entities include an unique ID to identify the user. The library card information that the user uploads is saved as a separate entity since one user can have many library cards linked to their account. Library entities will include the library name, since further information such as location and branch is unrelated to our current app, which only filters available books by which public library is accessible by the card you have linked.
 
## Entity-Relationship Diagram & Relational Model Diagram
![Screen Shot 2022-03-30 at 6 43 27 PM](https://user-images.githubusercontent.com/102686618/160943036-fde9afa4-b865-4883-ba54-59d7ac30d8da.png)

 
