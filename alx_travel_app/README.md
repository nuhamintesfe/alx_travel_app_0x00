# ALX Travel App 0x00

This is a Django-based web application built as part of the ALX Backend Development curriculum. It provides a foundation for a scalable travel and listings platform.

## 📁 Project Structure

alx_travel_app_0x00/
├── alx_travel_app/
│ ├── listings/
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ └── asgi.py
├── manage.py
├── requirement.txt
└── README.md

markdown
Copy
Edit

## 🚀 Features

- Modular Django structure with a `listings` app
- MySQL database integration via `django-environ`
- Swagger API documentation
- Admin interface for content management

## 🔧 Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nuhamintesfe/alx_travel_app_0x00.git
   cd alx_travel_app_0x00
Create and activate a virtual environment:

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate  # On Windows
Install dependencies:

bash
Copy
Edit
pip install -r requirement.txt
Create a .env file and configure your database settings. Example:

ini
Copy
Edit
DEBUG=True
SECRET_KEY=your-secret-key
DB_NAME=your_db_name
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_HOST=127.0.0.1
DB_PORT=3306
Run migrations and start the server:

bash
Copy
Edit
python manage.py migrate
python manage.py runserver
📜 License
This project is licensed under the MIT License.

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first.
