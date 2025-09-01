# E-Learning Complex Project

## Description
A comprehensive e-learning platform offering both technology and Quranic education courses. This platform aims to provide quality education in both modern technology skills and Islamic studies.

## Features
- Dual Learning Tracks: Technology & Quranic Studies
- Interactive Course Material
- Progress Tracking
- User-friendly Interface
- Course Categories:
  - Technology Courses
    - Programming
    - Web Development
    - Digital Skills
  - Quranic Studies
    - Quran Recitation
    - Islamic Studies
    - Arabic Language

## Technologies Used
- Frontend:
  - HTML5
  - CSS3
  - JavaScript
- Backend:
  - Python
  - Django Framework
- Database:
  - SQLite (Django ORM)
- Authentication:
  - Django Authentication System
- Media Handling:
  - Django Media Files
  - Video Streaming Support

## Installation
```bash
# Clone the repository
git clone https://github.com/saadsaeed-01/e-learning-complex-.git

# Navigate to project directory
cd e-learning-complex

# Create virtual environment
python -m venv venv

# Activate virtual environment
source venv/bin/activate  # On Linux/Mac
# or
venv\Scripts\activate  # On Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create superuser (Admin)
python manage.py createsuperuser

# Run development server
python manage.py runserver
```

## Current Status
🚧 **Project Status: Under Development** 🚧
- Currently implementing core features
- Expanding course content
- Enhancing user interface
- Adding more interactive elements


## Usage
1. Access admin panel at `/admin`
2. Access main site at `/`
(More detailed instructions will be added upon completion)

## License
Copyright (c) 2023 Saad Saeed. All rights reserved.

This software and associated documentation files (the "Software") are proprietary 
and confidential. The Software may be used and modified for personal use only.

Unauthorized copying, distribution, modification, public display, or public performance 
of this Software is strictly prohibited. No transfer of ownership or redistribution 
of the Software is allowed.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.