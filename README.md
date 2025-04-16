# Blog Application - Django

This is a fully-functional blog application built with Django, featuring user-generated content, comment systems, SEO optimization, and email notifications. The app allows users to create, view, and comment on blog posts, with various social features aimed at improving user engagement. It also includes advanced features such as full-text search and pagination for better content discoverability.

## Features
📝 Post Creation: Users can create blog posts, with features such as automatic sorting based on publication date.

💬 Comment System: Users can comment on posts, and the comment system is fully integrated with Django’s admin interface.

🔄 Pagination: Supports pagination for blog post listings to enhance user experience on content-heavy sites.

🔍 SEO-Friendly URLs: Implements canonical URLs and other optimizations to improve search engine ranking.

📧 Email Notifications: Users can receive email notifications for blog post recommendations and other activities.

🔍 Full-Text Search: Implemented PostgreSQL’s full-text search capabilities for efficient content discovery.

⚙️ Django Admin Interface: Custom admin interface for managing posts and comments.

## Technologies Used
- 🐍 Backend: Python, Django
- 🌐 Frontend: HTML, CSS
- 🗄️ Database: PostgreSQL
- 🐋 Containerization: Docker
- 🔍 Search Engine: PostgreSQL Full-Text Search
- 📧 Email Integration: Django's built-in email handling system
- 🧑‍💻 Version Control: Git, GitHub

## Installation

### Prerequisites
- Python 3.8+
- Django 3.0+
- PostgreSQL
- Docker (Optional, for deployment)

### Steps to Install Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blog-app.git
   cd blog-app
   ```

2. Set up a virtual environment:
   ```bash
   python3 -m venv env
   source env/bin/activate  # For Linux/MacOS
   .\env\Scripts\activate  # For Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up the PostgreSQL database:
   - Create a PostgreSQL database and user.
   - Update the database settings in `settings.py`.

5. Apply migrations:
   ```bash
   python manage.py migrate
   ```

6. Create a superuser (to access the Django admin interface):
   ```bash
   python manage.py createsuperuser
   ```

7. Run the development server:
   ```bash
   python manage.py runserver
   ```

8. Access the application:  
   Visit `http://127.0.0.1:8000/` in your browser to access the blog app.

### Running with Docker (Optional)
1. Build the Docker image:
   ```bash
   docker-compose build
   ```

2. Run the application in a container:
   ```bash
   docker-compose up
   ```

3. Access the application at `http://localhost:8000`.

## Contributing
🤝 Feel free to fork this repository and submit pull requests for any enhancements or bug fixes. All contributions are welcome!

## License
📜 This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- 📖 Django Documentation: https://docs.djangoproject.com/en/stable/
- 📝 PostgreSQL Full-Text Search: https://www.postgresql.org/docs/current/textsearch.html
- 🐳 Docker Documentation: https://docs.docker.com/

