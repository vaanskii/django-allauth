
# Django-allauth 

This is a simple Django project demonstrating how to integrate Django Allauth for authentication.

## Setup
1. Clone the repository:

```bash
git clone git@github.com:vaanskii/django-allauth.git
```

2.Navigate into the project directory:
```bash
cd django-allauth
```
3.Create a virtual environment:
```bash
python3 -m venv virtual-env-name
```
4. Activate the virtual environment:
- On Windows:
  ```
  env\Scripts\activate
  ```
- On macOS and Linux:
  ```
  source env/bin/activate
  ```

5. Install dependencies:
```
pip install -r requirements.txt
```

6. Apply migrations:
```
python manage.py migrate
```

7. Run the development server:
```
python manage.py runserver
```

8. Access the application in your web browser at http://127.0.0.1:8000/

## Usage

- To register a new account, go to the registration page by clicking on the "Sign Up" link.
- You can also sign in with your Google account by clicking on the "Login with Google" button.
- Once logged in, you can access your profile page by clicking on the "Profile" link.

## Technologies Used

- Python
- Django
- Django Allauth
- HTML

## Resources

- [Django Documentation](https://docs.djangoproject.com/)
- [Django Allauth Documentation](https://django-allauth.readthedocs.io/en/latest/)


