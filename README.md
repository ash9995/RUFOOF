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
* A local web server for development to handle ES6 module imports correctly. The [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension for VS Code is highly recommended.

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/rufuf-library-system.git](https://github.com/your-username/rufuf-library-system.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd rufuf-library-system
    ```

3.  **Open `index.html` with a live server:**
    * If you are using the VS Code Live Server extension, simply right-click on `index.html` and select "Open with Live Server".
    * This will open the application in your default browser, typically at `http://127.0.0.1:5500`.

---

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

For a detailed breakdown of the architecture, please see the project documentation.

---

## 👤 Default User Accounts

The system comes with a pre-configured administrator account:

* **Membership Number:** `ADMIN001`
* **Password:** `Admin@123`

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or want to fix a bug, please feel free to open an issue or submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License - see the `LICENSE` file for details.
