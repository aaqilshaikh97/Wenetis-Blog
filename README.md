# 📝 Wenetis Blog Application

## ✅ How to Run This Project (Step-by-Step)

Follow the steps below to clone and run the Django blog app locally.


## 1️⃣ Clone the repository
```bash
git clone https://github.com/aaqilshaikh97/Wenetis-Blog.git
cd Wenetis-Blog
```
## 2️⃣ Create and activate a virtual environment
```bash
## For Windows:
python -m venv env
env\Scripts\activate

## For macOS/Linux:
python3 -m venv env
source env/bin/activate
```
## 3️⃣ Install required packages
```bash
pip install -r requirements.txt

```

## 4️⃣ Apply migrations and create the database
```bash
python manage.py makemigrations
python manage.py migrate
```
## 5️⃣ Create a superuser (for accessing the admin panel)
```bash
python manage.py createsuperuser
```

When prompted, enter a username (e.g., admin), email address (e.g., admin@example.com), and password (it will ask you to confirm it).
## 6️⃣ Run the development server
```bash
python manage.py runserver

```
## 🌐 Access the App
```bash
Blog: http://127.0.0.1:8000/
Admin: http://127.0.0.1:8000/admin/
```