
# 📰 Django Blog

A clean and simple blog application built with **Python** and **Django**. This project is designed for publishing articles, managing content, and demonstrating the core features of a modern blog.

## ✨ Features

- Create, edit, and delete blog posts
- User authentication (login, logout, register)
- Django admin panel for content management
- Responsive templates with clean UI
- Blog post listing with pagination
- Post detail view with dynamic URLs

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/django-blog.git
   cd django-blog
   ```

2. **Set up virtual environment:**
   ```bash
   python -m venv env
   source env/bin/activate  # Windows: env\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser:**
   ```bash
   python manage.py createsuperuser
   ```

6. **Start development server:**
   ```bash
   python manage.py runserver
   ```

Access your site at: [http://127.0.0.1:8000](http://127.0.0.1:8000)

## 📌 Notes

- You can customize the blog by adding tags, categories, search, or a commenting system.
- For production use, replace SQLite with PostgreSQL and configure static/media file hosting.

## 🤝 Contributing

Feel free to fork the repo, open issues, or submit pull requests. Contributions are welcome!

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> Built with Django 🐍 by passionate developers.
