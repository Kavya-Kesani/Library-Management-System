# 📚 Library Management System using C

A simple console-based application written in C that allows users to manage a small library. The program provides functionalities to add, display, and search for books, as well as track the total number of books.

---

## 📌 Features

- 📖 Add new books to the library
- 🧾 Display all stored book information
- 🔍 Search and list all books by a specific author
- 📊 Show the total count of books in the library
- 🚪 Exit functionality to close the application

---

## 🛠️ Technologies Used

- **C Programming Language**
- Standard I/O (`stdio.h`)
- String manipulation (`string.h`)
- Program control and memory (`stdlib.h`)

---

## 🧾 How to Use

### 1. Compile the Program

Use any C compiler. For example, using `gcc`:

```bash
gcc -o LibraryManagement library.c
```

### 2. Run the Executable

```bash
./LibraryManagement
```

---

## 🖥️ Application Menu

```
**######WELCOME TO E-LIBRARY #####

1. Add book information
2. Display book information
3. List all books of given author
4. List the count of books in the library
5. Exit

Enter one of the above:
```

---

## 📋 Sample Output

```
Enter book name = CProgramming
Enter author name = Dennis
Enter pages = 250
Enter price = 300

You have entered the following information:
book name = CProgramming  author name = Dennis  pages = 250  price = 300.000000
```

---

## ⚠️ Notes

- Author and book name input are limited to single words due to `scanf("%s", ...)`.
- Book capacity is limited to 100 entries (`lib[100]`).
- Uses a simple `struct` to hold book details (`book_name`, `author`, `pages`, `price`).

---

## 🚀 Future Improvements

- Allow multi-word book and author names using `fgets()`.
- Enable saving and loading from files.
- Add support for deleting or editing book records.
- Build a GUI using C libraries like GTK.

---

## 📄 License

This project is open-source and free to use for learning and educational purposes.

---

## 🙋‍♀️ Author

**K.Kavya**  
🎓 Student, SRM University AP  
💻 Passionate about programming and building useful tools with C and C++.

---

## 📬 Contact

📧 Connect with me via Gmail: [kavyarambabu232@gmail.com](mailto:kavyarambabu232@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/kavya-kesani-700a51292](https://www.linkedin.com/in/kavya-kesani-700a51292)

---

---

⭐ *If you find this helpful, feel free to fork or star the repo!*
