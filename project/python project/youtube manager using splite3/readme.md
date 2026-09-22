# **YouTube Manager**

> *A simple command-line YouTube Manager built with Python and SQLite.*

---

## **📌 About the Project**

**YouTube Manager** is a simple **command-line application** built using **Python** and **SQLite**.

The application allows users to manage their YouTube videos directly from the terminal. Users can **add, view, update, and delete** videos, with all information stored in a local SQLite database.

---

## **✨ Features**

- **📋 List Videos** — View all saved videos.
- **➕ Add Video** — Add a new video with its name and duration.
- **✏️ Update Video** — Update an existing video's name and duration.
- **🗑️ Delete Video** — Remove a video from the database.
- **💾 SQLite Database** — Store video information locally.
- **🔢 Auto-generated IDs** — Each video gets a unique ID automatically.

---

## **🛠️ Technologies Used**

| **Technology** | **Purpose** |
|---|---|
| **Python** | Application logic |
| **SQLite** | Database storage |
| **sqlite3** | Python's built-in SQLite library |

> *No external Python packages are required.*

---

## **📂 Project Structure**

```text
youtube-manager/
│
├── youtube_manager.py
├── youtube_manager.db
└── README.md
