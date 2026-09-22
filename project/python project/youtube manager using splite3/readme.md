YouTube Manager

A simple command-line YouTube Video Manager built with Python and SQLite.

This project allows you to manage a list of YouTube videos using a local SQLite database. You can add, view, update, and delete videos directly from the terminal.

Features

📋 List all saved videos

➕ Add a new video

✏️ Update an existing video

🗑️ Delete a video

💾 Store video information in a SQLite database

🔢 Automatically generate a unique ID for each video

Technologies Used

Python 3

SQLite3

sqlite3 Python standard library

No external Python packages are required.

Project Structure
youtube-manager/
│
├── youtube_manager.py
├── youtube_manager.db
└── README.md


The youtube_manager.db file is created automatically when you run the application.

Database

The application uses SQLite to store video information.

The videos table contains:

Column	Type	Description
id	INTEGER	Unique ID for each video
name	TEXT	Name of the video
time	TEXT	Video duration
How to Run
1. Clone the repository
git clone https://github.com/sunjal21/youtube-manager.git

2. Open the project

Open the project folder in PyCharm or your preferred Python IDE.

3. Run the application
python youtube_manager.py


Depending on your system, you may need:

python3 youtube_manager.py

How to Use

When the application starts, you will see:

Youtube Manager | choose an option
1. List all videos
2. Add a video
3. Update a video
4. Delete a video
5. Exit app

Add a Video

Select:

2


Then enter the video name and duration.

Example:

Enter video name: Python Tutorial
Enter video duration/time: 15:30

List Videos

Select:

1


Example output:

1. | Python Tutorial | 15:30
2. | SQLite Tutorial | 20:45

Update a Video

Select:

3


Enter the ID of the video you want to update, followed by the new name and duration.

Delete a Video

Select:

4


Enter the ID of the video you want to delete.

Exit

Select:

5


The application will close and the database connection will be closed.

Future Improvements

Some possible improvements for this project:

Add video URLs

Add search functionality

Add categories or playlists

Add better input validation

Add error handling

Build a graphical user interface

Convert the application into a web application

Add timestamps for when videos are added

License

This project is created for learning and educational purposes.
