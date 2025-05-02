# ContactBook with Login
Login-secured Django contact vault—zero-bloat CRUD.

A simple Django app to manage personal contacts with authentication.

## Setup
1. `git clone <repo-url>`
2. `python -m venv venv && source venv/bin/activate`
3. `pip install django`
4. `python manage.py migrate`
5. `python manage.py runserver`

## Usage
- Navigate to `/accounts/login/` to log in.
- Create a superuser: `python manage.py createsuperuser`
- After login, you can add, edit, delete your own contacts.

### Optional
- Search contacts by name or email via the search bar.

