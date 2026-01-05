# 💰 Expense Tracker (Django)

A simple and user-friendly **Expense Tracker web application** built using **Django**.  
This application allows users to register, log in, add expenses, edit/delete them, filter by category, and view the total expense.

---

## 🚀 Features

- User authentication (Register / Login / Logout)
- Add, edit, and delete expenses
- Filter expenses by category
- Calculate total expenses
- Clean and modern UI
- Secure with Django CSRF protection

---

## 🛠️ Technologies Used

- Python
- Django
- HTML, CSS
- SQLite (default Django database)

---


---

## ⚙️ How to Run the Server

### 1️⃣ Clone the Project (if using Git)
```bash
git clone <repository-url>
cd expense_tracker

python -m venv myvenv
mvenv\Scripts\activate

pip install django
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

Now open - http://127.0.0.1:8000/

python manage.py createsuperuser
Enter the details
