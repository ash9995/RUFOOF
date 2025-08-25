# Rufuf - Library Management System 📚

**Rufuf** is a comprehensive, client-side Library Management System designed for efficient tracking of sources, members, and circulation within a library branch. Built with vanilla JavaScript, it provides a fast, responsive, and offline-first experience by leveraging the browser's `localStorage`.

The system is designed with a role-based access control system, catering to different user levels such as Librarians, Branch Supervisors, and System Administrators.

![Rufuf Screenshot](https://i.imgur.com/your-screenshot-url.png) ---

## ✨ Features

* **Dashboard:** An at-a-glance overview of key library statistics, recent activities, and employee performance.
* **Source Management:** Add, edit, delete, and search for library sources. Includes support for Dewey Decimal Classification.
* **Member Management:** Manage user accounts with different permission levels (Admin, Supervisor, Librarian).
* **Circulation Desk:** A streamlined interface for handling internal borrowing and returning of sources, designed for speed.
* **Advanced Search:** Powerful search capabilities to find sources by title, author, BIB number, and more.
* **Reporting & Analytics:** Generate detailed reports on daily activity, sources, members, and reading statistics.
* **Data Import/Export:** Easily import sources from Excel files and export data backups or report results.
* **Role-Based Access:** Securely control access to features based on user roles.
* **Client-Side Storage:** All data is stored in the browser's `localStorage`, making the application fast and usable offline.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6 Modules)
* **Libraries:** [SheetJS (xlsx.full.min.js)](https://sheetjs.com/) for Excel data processing.

---

## 🚀 Getting Started

The application is designed to run directly in a web browser without any server-side setup.

### Prerequisites

* A modern web browser (Chrome, Firefox, Edge).


## 📂 Project Structure

The project follows an **MVVM (Model-View-ViewModel)** architecture to ensure a clean separation of concerns:

```
/
├── index.html              # Main HTML file (the View)
├── app.js                  # Main application controller
├── services/               # Cross-cutting concerns (Auth, Storage)
├── models/                 # Data structures and constants
├── viewmodels/             # UI logic and state management
├── views/                  # DOM manipulation and rendering
├── utils/                  # Helper functions
└── styles/                 # CSS stylesheets
```



## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or want to fix a bug, please feel free to open an issue or submit a pull request.


