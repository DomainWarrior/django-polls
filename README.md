# django-polls

> A polls web app built with Django — create questions, vote, and see results in real time.

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python)
![Django](https://img.shields.io/badge/Django-3.1-092E20?style=flat-square&logo=django)
![Bulma](https://img.shields.io/badge/Bulma-CSS-00D1B2?style=flat-square)

> **Note:** Built as a learning project following the official Django tutorial. Django 3.1 is EOL — upgrade to Django 4.2+ or 5.x for new projects.

---

## Features

- Create poll questions with multiple choice answers
- Vote on active polls
- View live results after voting
- Django admin panel for managing questions
- Styled with Bulma CSS

---

## Setup

```bash
# Clone and enter the project
git clone https://github.com/DomainWarrior/django-polls.git
cd django-polls/polls

# Install dependencies
pip install django

# Run migrations
python manage.py migrate

# Create a superuser (for admin access)
python manage.py createsuperuser

# Start the dev server
python manage.py runserver
```

Open [http://localhost:8000/polls](http://localhost:8000/polls) to vote, or [http://localhost:8000/admin](http://localhost:8000/admin) to manage questions.

---

## Project structure

```
polls/
├── manage.py
├── poll/              # Polls app (models, views, templates)
│   ├── models.py      # Question & Choice models
│   ├── views.py       # Index, detail, results, vote views
│   └── templates/
│       └── polls/     # index.html, detail.html, results.html
└── polls/             # Project settings & URLs
```

---

## License

MIT © [DomainWarrior](https://github.com/DomainWarrior)