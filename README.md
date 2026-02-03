# Book--author--laravel
Laravel assignment for Book &amp; Author Management
# 📚 Book & Author Management System (Laravel)

## 📌 Project Overview
This is a simple **Laravel-based Backend API** for managing **Authors and their Books**.  
It demonstrates basic **CRUD operations**, proper **database relationships**, and **request validation**, as required in the assignment.

This project is built as part of a technical hiring assignment.

---

## 🚀 Features

- ✅ Create, Read, Update, Delete (**CRUD**) for Authors  
- ✅ Create, Read, Update, Delete (**CRUD**) for Books  
- ✅ One-to-Many Relationship:  
  - One **Author** can have multiple **Books**
- ✅ Proper database migrations  
- ✅ Request validation for API inputs  
- ✅ Clean and readable Laravel structure  

---

## 🛠️ Tech Stack

- **PHP**: 8.2  
- **Laravel**: Latest Version  
- **Database**: SQLite (default) / MySQL (configurable)  
- **Composer**  
- **Postman (for API testing)**  

---

## 📂 Project Structure (Important Files)
# 📚 Book & Author Management System (Laravel)

## 📌 Project Overview
This is a simple **Laravel-based Backend API** for managing **Authors and their Books**.  
It demonstrates basic **CRUD operations**, proper **database relationships**, and **request validation**, as required in the assignment.

This project is built as part of a technical hiring assignment.

---

## 🚀 Features

- ✅ Create, Read, Update, Delete (**CRUD**) for Authors  
- ✅ Create, Read, Update, Delete (**CRUD**) for Books  
- ✅ One-to-Many Relationship:  
  - One **Author** can have multiple **Books**
- ✅ Proper database migrations  
- ✅ Request validation for API inputs  
- ✅ Clean and readable Laravel structure  

---

## 🛠️ Tech Stack

- **PHP**: 8.2  
- **Laravel**: Latest Version  
- **Database**: SQLite (default) / MySQL (configurable)  
- **Composer**  
- **Postman (for API testing)**  

---

## 📂 Project Structure (Important Files)
book-author-management/
│
├── app/
│ ├── Models/
│ │ ├── Author.php
│ │ └── Book.php
│ └── Http/Controllers/
│ ├── AuthorController.php
│ └── BookController.php
│
├── database/
│ └── migrations/
│
├── routes/
│ └── api.php
│
├── public/
├── bootstrap/
├── config/
├── resources/
├── storage/
├── tests/
│
├── artisan
├── composer.json
├── composer.lock
├── .env.example
└── .gitignore


---

## ⚙️ Setup Instructions (For Reviewer)

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Phagyarekha40/Book-author-laravel.git
cd Book-author-laravel

2️⃣ Install dependencies
composer install

3️⃣ Environment setup

Copy the example file:

cp .env.example .env


Generate application key:

php artisan key:generate

4️⃣ Database setup (SQLite - default)

Make sure this file exists:

database/database.sqlite


If not, create it:

touch database/database.sqlite


Run migrations:

php artisan migrate

5️⃣ Run the server
php artisan serve


Open in browser:

http://127.0.0.1:8000

🔗 API Endpoints
Authors
Method	Endpoint	Description
GET	/api/authors	Get all authors
POST	/api/authors	Create an author
GET	/api/authors/{id}	Get single author
PUT	/api/authors/{id}	Update author
DELETE	/api/authors/{id}	Delete author
Sample Request (Create Author)
POST /api/authors
{
  "name": "J.K. Rowling",
  "email": "jk@example.com"
}

Books
Method	Endpoint	Description
GET	/api/books	Get all books
POST	/api/books	Create a book
GET	/api/books/{id}	Get single book
PUT	/api/books/{id}	Update book
DELETE	/api/books/{id}	Delete book
Sample Request (Create Book)
POST /api/books
{
  "title": "Harry Potter",
  "author_id": 1
}




---



📧 Contact

If you have any questions regarding this project, feel free to reach out.

Developed by: Rekha
email=rekhapasupuleti34@gmail.com


---


