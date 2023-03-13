# Django Boiler Plate

This is a project to manage the stores for renting and usage

## Requirements

- Poetry (`pip install poetry`)
- pre-commit (`pip install pre-commit`)

## Setup

1. Clone the Repo

    ```bash
    git pull origin https://github.com/MuhammadHassan1998/storage_unit.git
    cd storage_unit
    ```

2. Install the project: `poetry install`

3. Set up pre-commit: `pre-commit install`

4. populate `.env`:

    Add a `.env` file in the repo root.
    important values to run the project

    ```sh
    NAME: 'myproject',
    USER: 'root',
    PASSWORD: 'root',
    HOST: 'localhost',
    PORT: '',
    ```
5. Run `python manage.py makekigrations`

6. Run `python manage.py makemigrate`

7. Run `Python manage.py runserver`

    _**Note:** You need to run the postgresql server first and create the db
    the site will run on http://localhost:8000

    Run `pre-commit run --all-files` before comiting to run black and isort on all files
