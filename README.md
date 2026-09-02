# 🐍 Django Learning

## 📌 Project Description

This is a Blog Web Application built using **Python, Django, MySQL, HTML, CSS, and Bootstrap**.
The project was developed while learning Django from scratch and covers core Django concepts including URL routing, views, templates, models, MySQL database integration, forms, pagination, admin customization, custom management commands, and dynamic content.

---

## 🚀 Features

### 📝 Blog Posts

* Display blog posts dynamically
* Fetch posts dynamically from MySQL database
* Post detail page using dynamic slug
* Display post title, content, image, category, and created date
* Display related posts based on category

### 🗂️ Categories

* Create and manage categories
* Assign categories to posts
* Display category name with posts
* Filter posts by category in Django Admin

### 📄 Pagination

* Display posts page by page
* Display 5 posts per page
* Navigate between different pages

### 📬 Contact Form

* Contact form using Django Forms
* Name, email, and message fields
* Server-side form validation
* Display validation errors
* Display success message after valid submission

### ℹ️ About Us

* Dynamic About Us page
* About Us content stored in MySQL database
* Manage About Us content through Django Admin
* Display database content dynamically in the template

### 🔐 Admin

* Django Admin integration
* Register Post, Category, and AboutUs models
* Custom PostAdmin configuration
* Search posts by title and content
* Filter posts by category and created date

### 🔄 URL & Navigation

* Named URLs
* URL namespaces
* Dynamic URL segments
* Reverse URL
* URL redirects
* Custom 404 error handling

---

## 🛠️ Technologies Used

* Python
* Django 5.2
* MySQL
* HTML5
* CSS3
* Bootstrap 5
* Git & GitHub

---

## 🗄️ Database

MySQL is used as the database for this Django project.

### Models

* `Post`
* `Category`
* `AboutUs`

### Post Fields

* `title`
* `content`
* `img_url`
* `created_at`
* `slug`
* `category`

### Category Fields

* `name`

### AboutUs Fields

* `content`

---

## 🔄 CRUD Operations

### Create

* Create blog posts
* Create categories
* Create About Us content
* Submit contact form

### Read

* Fetch blog posts
* Fetch post details
* Fetch categories
* Fetch related posts
* Fetch About Us content

### Update

* Update blog posts
* Update categories
* Update About Us content through Django Admin

### Delete

* Delete posts
* Delete categories
* Delete About Us content

---

## 🧩 Project Structure

```text
myapp
│
├── manage.py
│
├── myapp
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
└── blog
    ├── migrations
    │
    ├── management
    │   └── commands
    │       └── populate_posts.py
    │
    ├── templates
    │   └── blog
    │
    ├── static
    │
    ├── admin.py
    ├── apps.py
    ├── forms.py
    ├── models.py
    ├── urls.py
    ├── views.py
    └── __init__.py
```

---

## ▶️ How to Run the Project

### 1. Setup the Virtual Environment

Create a virtual environment:

```bash
python -m venv env
```

Activate the virtual environment:

```bash
.\env\Scripts\activate
```

### 2. Install Django

```bash
pip install Django
```

Or install Django 5.2:

```bash
pip install "Django==5.2.*"
```

### 3. Start the Django Project

```bash
django-admin startproject myapp
```

### 4. Open the Project Folder

```bash
cd myapp
```

### 5. Create the Blog App

```bash
python manage.py startapp blog
```

### 6. Install MySQL Client

Install `mysqlclient` for MySQL database connectivity:

```bash
pip install mysqlclient
```

Configure the MySQL database in `settings.py`.

### 7. Create Migrations

```bash
python .\manage.py makemigrations
```

### 8. Apply Migrations

```bash
python .\manage.py migrate
```

### 9. Insert Demo Data

```bash
python .\manage.py populate_posts
```

### 10. Install Pagination

```bash
pip install django-pagination
```

### 11. Create Django Superuser

```bash
python .\manage.py createsuperuser
```

Enter the required details:

```
Username:
Email:
Password:
Password (again):
```

### 12. Run the Development Server

```bash
python manage.py runserver
```

---

## 🌐 Application URLs

### 🏠 Home Page

```
http://127.0.0.1:8000/
```

### 📝 Post Detail

```
http://127.0.0.1:8000/post/<slug>
```

### 📬 Contact Page

```
http://127.0.0.1:8000/contact
```

### ℹ️ About Us Page

```
http://127.0.0.1:8000/about
```

### 🔐 Django Admin

```
http://127.0.0.1:8000/admin/
```

---

## 🧪 Custom Management Command

Faker is used to generate demo data for the blog.

Run the custom management command:

```bash
python .\manage.py populate_posts
```

This command inserts sample blog posts and assigns categories to the posts.

---

## 🛠️ Django Admin Customization

The Post Admin interface includes:

* Custom list display
* Search by title and content
* Filter by category
* Filter by created date

Registered models:

* `Post`
* `Category`
* `AboutUs`

---

## 📚 Django Concepts Learned

* Django Project Setup
* Virtual Environment
* Django App Creation
* URL Configuration
* Views
* HTTP Response
* Dynamic URL Segments
* Named URLs
* URL Namespace
* URL Reverse
* Redirects
* Templates
* Template Inheritance
* Static Files
* Template Filters
* Template Tags
* Custom 404 Page
* Django Logger
* MySQL Connectivity
* Django Models
* ForeignKey Relationships
* Migrations
* CRUD Operations
* Django Forms
* Form Validation
* Pagination
* Custom Management Commands
* Faker
* Django Admin
* Admin Customization
* Dynamic Database Content
* Authentication

---

## 📌 Future Improvements

* ❤️ Like & Unlike Posts
* 💬 Add Comments
* 🔍 Search Posts
* 👤 User Profile
* 📸 Image Upload
* 📧 Email Integration
* 🔐 Password Reset
* 🌐 Deploy the Application

---

## 🙋‍♂️ Author

**Sivaponnuvel S**

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
