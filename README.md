# book-service

This is a backend service for Kanbook. This service stores books that users are wanting to read, reading, or have read.

## Tables of Contents

1. [Local Setup](#local-setup)

## Local Setup

1. Generate a virtual environment.
    - `python3 -m venv env`
2. Activate the virtual environment from the root.
    - `source env/bin/activate`
3. Install requirements.
    - `pip3 install -r requirements.txt`
4. Run migrations.
    - `python3 manage.py migrate`
5. Start the server.
    - `python3 manage.py runserver`