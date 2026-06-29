# ScoopVerse - Premium Ice Cream Shop Website

## Overview

ScoopVerse is a modern Django-based ice cream shop website designed to showcase premium handcrafted ice cream products. The website provides an attractive user interface, product listings, company information, and a contact form for customer inquiries.

## Features

* Responsive and modern website design
* Home page with featured ice cream flavors
* Products page showcasing available flavors
* About page with brand information
* Contact page with customer inquiry form
* Database integration using Django ORM
* Static image and CSS support
* Clean navigation between pages

## Technologies Used

* Python
* Django
* HTML5
* CSS3
* SQLite3
* Django Templates

## Project Structure

```text
scoop_project/
│
├── scoop_app/
│   ├── templates/
│   ├── static/
│   ├── models.py
│   ├── views.py
│   └── urls.py
│
├── db.sqlite3
├── manage.py
└── requirements.txt
```

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

```bash
cd scoop_project
```

3. Create and activate a virtual environment:

```bash
python -m venv venv
```

Windows:

```bash
venv\Scripts\activate
```

4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Apply migrations:

```bash
python manage.py migrate
```

6. Run the development server:

```bash
python manage.py runserver
```

7. Open your browser and visit:

```text
http://127.0.0.1:8000/
```

## Contact Form

The contact page allows visitors to submit inquiries. Submitted messages are stored in the database using Django models.

## Future Improvements

* User authentication system
* Online ordering functionality
* Shopping cart integration
* Payment gateway support
* Admin dashboard enhancements
* Product categories and filtering

## Author

Sharif Ur Rehman

## License

This project is created for educational and portfolio purposes.

