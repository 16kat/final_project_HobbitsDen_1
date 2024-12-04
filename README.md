Team Name: Hobbit’s Den 

Team Member: Talia Katebi 

Welcome to Hobbit’s Den!!! Your Personal Book Journal awaits!
This guide will walk you through the features and controls of the Book Journal application.
Hello and welcome to Hobbit’s Den, a Java-based application designed to act as a personal book journal. It provides an organized and intuitive platform for users to log, manage, and reflect on their reading experiences. The application offers features such as adding books, viewing a library of entries, and searching for specific books by title. Its goal is to create a simple, yet efficient tool tailored to enhance the reading experience and revisit cherished stories. Whether the user is a casual reader or a dedicated book lover, Hobbit’s Den provides an organized way to reflect on the books that have been read and keep the users motivated to keep reading. This tool is useful for building personal reading history and revisiting favorite books or notes in the future.
________________________________________ 
 Components of Hobbit's Den
1.	Book Class
Represents a book with attributes such as title, author, genre, date finished, rating, and notes.
o	Includes getter and setter methods for all attributes.
o	Provides functionality to display a detailed description and a brief overview of the book.
2.	BookJournal Class
Manages a collection of books categorized by user.
o	Supports adding books, retrieving a user's books, and saving/loading book data to/from a file.
o	Uses a HashMap to associate usernames with their respective book lists.
3.	hobbitsden (Main Class)
The primary entry point of the application, which uses JavaFX for the graphical user interface (GUI).
o	Main Features:
	Add Book: Users can input details of a new book to add to their journal.
	View My Books: Displays all books added by the current user, with options to view details, edit, or delete books.
	Search Books: Allows searching for books by title within the user's collection.
o	User Experience:
	Displays a personalized welcome message and organizes books by the current user.
	Provides dynamic updates and persistent storage using serialized files.
________________________________________
Using the Application
Using Hobbit’s Den is easy. Upon launching the application, you'll be prompted to enter your username. This ensures your book records are saved and accessible under your profile. If you’re new, simply type a desired username to get started. Once you start, you’ll have the option to:

•	Add Books: Enter details about the book, including the title, author, genre, start and end dates, and any notes you want to remember.
•	View My Books: See a complete list of your logged books at any time.
•	Search Books: Quickly find a specific book by searching by title, author, or genre. 
•	Exit: Use the Exit button to close the application safely when you're done. 
________________________________________
Adding a Book
•	Click the Add Book button. A form will appear to input the following details:
o	Title
o	Author
o	Genre
o	Date Finished (in YYYY-MM-DD format)
o	Rating (1-5 stars)
o	Personal Notes
•	Once you’ve filled out the fields, click Add Book to save your entry. An alert will confirm successful addition.
________________________________________
Viewing Your Library
•	Click the View My Books button to see all the books you’ve logged. Each entry will display the book’s title and author, along with three action buttons:
o	View Details: Shows all the details saved about the book.
o	Edit: Opens a form to modify book details.
o	Delete: Permanently removes the book from your journal after confirmation.
________________________________________
Searching for a Book
•	Click Search Books to locate a specific book by its title.
•	Enter a keyword or phrase in the search bar and hit Search. Matching results will display with options to view details for each book.
________________________________________
Exiting the Application
•	Click the Exit button to close the application. Your book journal is automatically saved to ensure no data is lost.
________________________________________
Important Notes
Data Persistence: All your book data is saved locally in a file named book_journal.dat. This ensures your journal is available every time you reopen the app.
________________________________________
Keyboard Shortcuts
While the application primarily uses mouse interactions, a helpful tip:
•	Press Enter to confirm text inputs in dialogs (e.g., username entry).
________________________________________
Future Improvements
Here are features planned for future updates:
•	Enhanced search filters (e.g., by genre, rating, or author).
•	Exporting book lists to a file or sharing them online.
________________________________________
I hope you enjoy using Hobbit's Den to catalog your reading adventures. Happy journaling!


