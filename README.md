# Peer File Sharing Network

This Flask-based web application allows users to securely register, log in, and share files with others in a peer-to-peer manner. It includes features for file searching, secure downloads, and robust session management.

## Features

- User Registration and Login: Secure user authentication with a SQLite database.
- Dashboard: Personalized dashboard for logged-in users.
- File Sharing: Share files with details such as size and type stored in the database.
- File Searching: Search for shared files by name or type.
- File Download: Secure file download functionality.
- Session Management: Protect access to private resources.

## Prerequisites

Ensure you have the following installed:

- Python 3.7+
- Flask (pip install flask)
- SQLite (default with Python)
- mimetypes for file type detection
- os for file operations
