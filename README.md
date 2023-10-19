# Django Task Manager

This folder contains project code for building a Task Manager  app with Django.

## Setup Instructions

1. Navigate into the project directory (`source_code/`).
2. Create a virtual environment in a `venv/` folder by typing `python -m venv venv` in your console.
3. Activate the venv using  `venv\Scripts\activate` (Windows).
4. Install the dependencies with `python -m pip install -r requirements.txt`
5. Generate the empty SQLite database and tables using `python manage.py migrate`
5. Run the app with `python manage.py runserver`
6. Browse to the [app home page](http://localhost:8000/) to see the list of task list, which will initially be empty. 

You can now start using the UI to add your to-do lists and to-do items to the database. The data will be stored in a new `db.sqlite3` file in the root of your project directory.

You can also use Django's auto-generated [admin interface](https://realpython.com/customize-django-admin-python/#setting-up-the-django-admin) at `http://localhost:8000/admin/` to view, add, and edit the data.
