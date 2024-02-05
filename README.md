# Fingerprint Attendance System

The Fingerprint Attendance System is a modern solution designed to automate the attendance process using biometric fingerprint identification. This system is ideal for educational institutions, offices, and any setting where attendance tracking is essential. It provides a secure and efficient way to manage and record attendance data.

## Project Structure

- `__pycache__`: Contains Python 3 bytecode compiled and cached files to speed up program startup.
- `keys`: Stores secure keys and credentials needed for the application's operation.
- `public/sounds`: Contains sound files used for notifications or alerts within the application.
- `students`: Holds data related to students or participants whose attendance is tracked.
- `utils`: Includes utility scripts and modules that provide support functions for the application.
- `views`: Contains files responsible for the application's front-end views and templates.
- `app.py`: The main Python script that runs the Flask web application.
- `matcher.py`: Handles the logic for matching fingerprints against the stored data.
- `package-lock.json` & `package.json`: Node.js configuration files for managing project dependencies.
- `query.dib`: Stores database queries or schema definitions (ensure this is meant to be `.db` for a database file).
- `server.js`: The Node.js server script for handling backend logic and routes.
- `success.html`: HTML template displayed upon successful attendance registration.
- `test.html`: HTML template for testing or demonstration purposes.
