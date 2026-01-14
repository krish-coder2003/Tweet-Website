# Tweet-Website

A beautiful Django project where users can create, edit, delete and view tweets with image support — similar to a mini social media platform.

This project is built with Django and Bootstrap, and includes features like user authentication, image uploads, and modern UI.

---

## 🚀 Features

✨ User authentication (Register, Login, Logout)  
✏ Create, edit and delete tweets  
🖼️ Upload images with tweets  
⚡ Clean responsive UI with Bootstrap  
🔒 Authorization so users can only edit/delete their own tweets

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python      | Backend language |
| Django      | Web framework |
| Bootstrap 5 | Front-end styling |
| SQLite     | Development database |

---

Tweet-Website/
├── tweet/
│ ├── migrations/
│ ├── templates/
│ ├── views.py
│ ├── models.py
│ ├── forms.py
│ └── urls.py
├── chaiheadq/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── templates/
│ ├── layout.html
├── static/
├── media/
├── db.sqlite3
├── .gitignore
├── manage.py
└── requirements.txt


---

## 📌 Installation (Local Setup)

### 1. Clone the repository

```bash
git clone https://github.com/krish-coder2003/Tweet-Website.git
cd Tweet-Website

2. Create and activate virtual environment

Windows:

python -m venv .venv
.venv\Scripts\activate


Mac / Linux:

python3 -m venv .venv
source .venv/bin/activate

3. Install dependencies
pip install -r requirements.txt
💾 Database Setup

Apply migrations:

python manage.py makemigrations
python manage.py migrate

👤 Create Superuser (Optional)

If you want admin access:

python manage.py createsuperuser

▶️ Run the Development Server
python manage.py runserver


Open your browser at http://127.0.0.1:8000/ to see the application.

📝 Usage

✔ Register a new user
✔ Login
✔ Create a tweet (with optional image)
✔ Edit or delete your own tweets
✔ View tweets from all users

📌 Notes

✔ Images are stored in /media/photos/
✔ Protect sensitive settings with environment variables in production
✔ This project uses Bootstrap 5 for UI

❤️ Contributing

Contributions are welcome! Steps to contribute:

Fork the repository

Create a new branch

git checkout -b feature/awesome-feature


Commit your changes

git commit -m "Add awesome feature"


Push to your fork

git push origin feature/awesome-feature


Open a Pull Request

📄 License

This project is open-source under the MIT License.

🙌 Thank You

Thanks for checking out Tweet-Website — built with ❤️ using Django!


---

### ✨ How To Add It

1. In your repo root (where `manage.py` is), create a file named:
## 📁 Folder Structure

