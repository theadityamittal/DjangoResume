# Django Resume Project

This project is a simple resume website built with Django. The website displays personal information, skills, experience, education, and projects.

## Features

- Displays personal information such as name, contact details, and social media links.
- Lists skills in various domains.
- Highlights professional experience and roles.
- Describes educational background.
- Showcases notable projects with descriptions and tech stacks.

## Prerequisites

- Python 3.x
- Django 5.1.6
- Git (for cloning the repository)

## Installation

1. **Clone the Repository:**

   ```bash
   git clone <repository-url>
   cd djangoresume
   ```

2. **Create a Virtual Environment:**

   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment:**

   - On Windows:

     ```bash
     .\venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Install the Requirements:**

   ```bash
   pip install -r requirements.txt
   ```

## Running the Project

1. **Apply Migrations:**

   ```bash
   python manage.py migrate
   ```

2. **Run the Development Server:**

   ```bash
   python manage.py runserver
   ```

3. **Access the Website:**

   Open your browser and go to `http://127.0.0.1:8000` to view the resume website.

## Project Structure

- `djangoresume/` - The main Django project directory.
- `resume/` - The app directory containing templates, views, models, and URLs.
- `static/` - Directory for static files like CSS.
- `templates/` - Directory containing HTML templates.
- `requirements.txt` - File to list Python dependencies.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
