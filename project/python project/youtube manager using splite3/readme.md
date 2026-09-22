**YouTube Manager**

A simple command-line YouTube Manager built with Python and SQLite.

This project allows you to manage your YouTube videos from the terminal. You can add, view, update, and delete videos, with all data stored in a local SQLite database.

*Features*

 📋 List all videos

 ➕ Add a new video

 ✏️ Update an existing video

 🗑️ Delete a video

 💾 Store video data using SQLite

 🔢 Automatically generate unique video IDs

*Technologies Used*

Python

SQLite

sqlite3 — Python's built-in SQLite library

No external Python packages are required.

*How It Works*

The application provides a simple menu in the terminal:

Youtube Manager | choose an option

1. List all videos
2. Add a video
3. Update a video
4. Delete a video
5. Exit app


Select an option by entering the corresponding number.

Database

The application creates a SQLite database named:

youtube_manager.db


It contains a videos table with the following columns:

*Column	Type	Description*
id	INTEGER	Unique ID of the video
name	TEXT	Name of the video
time	TEXT	Duration of the video

The database and table are created automatically when the application is run.

*Running the Project*
1. Clone the Repository
git clone https://github.com/sunjal21/youtube-manager.git

2. Open the Project

Open the downloaded project in PyCharm or any Python IDE.

3. Run the Application

Run the Python file containing the application:

python youtube_manager.py


You can also run it directly from PyCharm by clicking the Run button.

Example
Adding a Video
Enter your choice: 2
Enter video name: Python Tutorial
Enter video duration/time: 15:30

*Listing Videos*
Enter your choice: 1

1. | Python Tutorial | 15:30

Updating a Video
Enter your choice: 3
Enter video ID to update: 1
Enter updated video name: Python Full Tutorial
Enter updated video duration/time: 20:45

Deleting a Video
Enter your choice: 4
Enter video ID to delete: 1

Project Structure
youtube-manager/
│
├── youtube_manager.py
├── youtube_manager.db
└── README.md


youtube_manager.db is generated automatically when the application runs.

*Future Improvements*

Add YouTube video URLs

Add search functionality

Add categories or playlists

Add input validation

Add error handling

Add a graphical user interface

Convert the project into a web application

*Author*

Sunjal

*GitHub: sunjal21*
