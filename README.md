# 📔 Personal Journal Manager

### ✍️ Write Your Thoughts. Save Your Memories. 💙

A simple, beginner-friendly **Python command-line application** that lets you record your daily thoughts, view previous journal entries, search entries using keywords or dates, and delete all saved entries.

Every journal entry is automatically saved with a timestamp, helping you keep your personal memories organized in a local text file.

---

## 📌 Table of Contents

- [✨ Features](#-features)
- [🛠️ Technologies Used](#️-technologies-used)
- [📂 Project Structure](#-project-structure)
- [⚙️ Installation](#️-installation)
- [🚀 How to Run](#-how-to-run)
- [📖 How to Use](#-how-to-use)
- [🖥️ Application Menu](#️-application-menu)
- [🧠 Learning Outcomes](#-learning-outcomes)
- [⭐ Why This Project?](#-why-this-project)
- [📸 Screenshots](#-screenshots)
- [🌱 Future Improvements](#-future-improvements)
- [📊 Future Project Roadmap](#-future-project-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [⭐ Support](#-support)
- [👨‍💻 Author](#-author)

---

## ✨ Features

### 📝 Add a New Entry
- Write and save personal journal entries.
- Automatically records the current date and time.
- Appends new entries without overwriting existing ones.

### 📖 View All Entries
- Display previously saved journal entries.
- Read your memories directly from the terminal.

### 🔍 Search Entries
- Search journal entries using keywords or dates.
- Supports case-insensitive text searching.
- Displays a message when no matching entries are found.

### 🗑️ Delete All Entries
- Delete the journal file and all its saved entries.
- Requires confirmation before deleting your journal.
- Allows you to cancel the deletion.

### 💾 Local File Storage
- Stores entries in a local `journal.txt` file.
- Preserves entries between program executions.
- Does not require a database or internet connection.

### 🛡️ Basic Error Handling
- Handles invalid menu inputs.
- Detects when the journal file does not exist.
- Provides error messages for common file operations.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python 3 | Core programming language |
| `datetime` | Generate timestamps for journal entries |
| `os` | Delete the journal file |
| File Handling | Read and write journal entries |
| Object-Oriented Programming | Organize functionality inside a class |
| Exception Handling | Handle errors and invalid inputs |

---

## 📂 Project Structure

```text
Personal-Journal-Manager/
│
├── main.py          # Main Python application
├── journal.txt      # Created automatically when an entry is added
├── README.md        # Project documentation
└── LICENSE          # Optional license file
```

**Note:** Use the filename of your actual Python script in place of `main.py`. The `journal.txt` file is generated when you save your first entry. The license file is optional.

---

## ⚙️ Installation

### Prerequisites

- Python 3.8 or later
- A code editor such as Visual Studio Code
- A terminal or command prompt

### Step 1: Clone the Repository

```bash
git clone https://github.com/Rami-Manan/-File-Operator.git
```

Replace `YOUR_REPOSITORY_URL` with your actual GitHub repository URL.

### Step 2: Open the Project Folder

```bash
cd Personal-Journal-Manager
```

### Step 3: Verify Python Installation

```bash
python --version
```

If your system uses the Python launcher on Windows, you can also run:

```bash
py --version
```

---

## 🚀 How to Run

Open the terminal inside your project directory and execute:

```bash
python main.py
```

On Windows, you can alternatively use:

```bash
py main.py
```

No external Python packages are required. The project uses Python's standard library.

---

## 📖 How to Use

### 1️⃣ Add a New Entry

Select option `1` and enter your thoughts.

Example:

```text
Enter your journal entry:
Today I learned file handling in Python.

Entry added successfully.
```

### 2️⃣ View All Entries

Select option `2` to display your saved entries.

Example:

```text
Your Journal Entries:
-------------------------------------
[2026-10-04 20:30:15] Today I learned file handling in Python.
```

### 3️⃣ Search for an Entry

Select option `3` and enter a keyword or date.

Example:

```text
Enter keyword or date to search: Python

[2026-10-04 20:30:15] Today I learned file handling in Python.
```

### 4️⃣ Delete All Entries

Select option `4` to remove the journal file.

```text
Are you sure you want to delete all entries? (yes/no): yes

All journal entries have been deleted.
```

**Warning:** Deletion removes the entire journal file. Back up your entries before using this option.

### 5️⃣ Exit the Application

Select option `5` to close the program safely.

```text
Thank you for using Personal Journal Manager. Goodbye!
```

---

## 🖥️ Application Menu

```text
Welcome to Personal Journal Manager!
Please select an option.

1. Add a New Entry
2. View all Entries
3. Search for an Entry
4. Delete all Entries
5. Exit

user Input:
```

---

## 🧠 Learning Outcomes

By building this project, you can practice:

- ✅ Object-Oriented Programming (OOP)
- ✅ Python classes and objects
- ✅ Constructors and instance variables
- ✅ File handling using `open()`, `read()`, `write()`, and `close()`
- ✅ File modes such as append (`a`) and read (`r`)
- ✅ Exception handling using `try`, `except`, and `FileNotFoundError`
- ✅ Conditional statements and loops
- ✅ User input and output
- ✅ String methods such as `lower()` and `strip()`
- ✅ Searching text using keywords
- ✅ Date and time formatting with `datetime`
- ✅ Basic operating-system operations using `os`

**Learning path:**

`Python Basics → Functions → OOP → File Handling → Exception Handling → Real-World Projects`

---

## ⭐ Why This Project?

Personal Journal Manager is a beginner-friendly project that combines several essential Python concepts into one practical application.

Instead of practicing each concept separately, you can see how classes, loops, conditions, timestamps, file operations, and exception handling work together in a real program.

This project is especially useful for students who want to strengthen their Python fundamentals and build a practical GitHub portfolio.

---

## 📸 Screenshots

Add screenshots of your actual application output here to make your GitHub repository more professional.

Recommended screenshots:

1. Main menu
2. Adding a journal entry
3. Viewing saved entries
4. Searching for an entry
5. Deleting entries with confirmation

Create a folder named `screenshots` and place your images inside it.

Example Markdown:

```markdown
## 📸 Screenshots

### Main Menu
![Main Menu](screenshots/main-menu.png)

### Add Journal Entry
![Add Entry](screenshots/add-entry.png)

### View Journal Entries
![View Entries](screenshots/view-entries.png)

### Search Journal Entry
![Search Entry](screenshots/search-entry.png)
```

Replace these placeholder paths with screenshots you have actually added to your repository.

---

## 🌱 Future Improvements

The project can be upgraded with several useful features.

### 🔮 Possible Future Features

- 🔐 Password protection
- 🗄️ SQLite database integration
- 🎨 Graphical User Interface (GUI)
- 🌙 Dark mode
- 📅 Calendar-based journal navigation
- 📄 Export journal entries to PDF
- ☁️ Cloud backup and synchronization
- 😊 Mood tracking
- 🏷️ Categories and tags
- 📊 Journal statistics and writing streaks
- 🔎 Advanced search and filtering
- ✏️ Edit existing journal entries
- 📱 Web application version
- 🔒 Encryption for private journal entries

These are planned enhancements, not features currently implemented in this version.

---

## 📊 Future Project Roadmap

### Version 1.0 — Current Version

- [x] Add journal entries
- [x] View saved entries
- [x] Search entries by keyword or date
- [x] Delete all entries
- [x] Add timestamps
- [x] Handle common errors
- [x] Store data in a text file

### Version 2.0 — Better Organization

- [ ] Edit individual entries
- [ ] Delete individual entries
- [ ] Add categories and tags
- [ ] Improve search and filtering
- [ ] Add a date-based journal view

### Version 3.0 — Advanced Features

- [ ] Build a graphical user interface
- [ ] Integrate an SQLite database
- [ ] Add password protection
- [ ] Implement journal encryption
- [ ] Add PDF export
- [ ] Develop a web application

---

## 🤝 Contributing

Contributions and suggestions are welcome!

To contribute:

1. Fork this repository.
2. Create a new branch.
3. Make your changes.
4. Test your code.
5. Submit a pull request.

You can also open an issue to report a bug or suggest a new feature.

---

## 📄 License

This project can be distributed under the MIT License if you choose to license it that way.

If you use the MIT License, add a `LICENSE` file containing the appropriate MIT license text. Until then, the project license is unspecified.

---
[![Architecture diagram of rami-manan/-file-operator](https://gitdiagram.com/rami-manan/-file-operator/diagram.png)](https://gitdiagram.com/rami-manan/-file-operator?utm_source=readme&utm_medium=picture)

## ⭐ Support

If you find this project useful:

- ⭐ Star this repository.
- 🍴 Fork the repository.
- 💻 Try running the project.
- 📢 Share it with other Python learners.
- 💡 Suggest new features or improvements.

Every bit of feedback helps make the project better!

---

## 👨‍💻 Author

**Manan Rami**

🐍 Python Learner | 💻 Programmer | 📚 Student

**Skills practiced:** Python • OOP • File Handling • Exception Handling • Git • GitHub

- 🐙 GitHub: [Your GitHub Profile](https://github.com/)

---

<div align="center">

### ✍️ Write Your Thoughts. Save Your Memories. 💙

**Made with ❤️ and Python 🐍**

</div>

