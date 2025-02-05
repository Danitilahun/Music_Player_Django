# Music Player App (Django)

A simple music player web application built with Django that allows users to play audio files. Users can upload and play music files directly from the server, with a clean and easy-to-use interface.

## Features

- **Audio File Upload**: Users can upload music files.
- **Music Playback**: Play uploaded music files directly from the server.
- **Simple Interface**: Easy-to-use web interface to control music playback.

## Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS
- **Database**: SQLite (for managing file metadata)

## Installation

Follow these steps to set up the project locally.

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Danitilahun/Music_Player_Django.git
   cd Music_Player_Django
   ```

2. **Create a virtual environment**:

   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Install the dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

5. **Run migrations**:

   ```bash
   python manage.py migrate
   ```

6. **Run the server**:

   ```bash
   python manage.py runserver
   ```

```