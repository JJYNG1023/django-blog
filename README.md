# Django Blog

A simple Django blog application.

## Setup

1. Create virtual environment:
   ```bash
   python3 -m venv venv
   ```

2. Activate virtual environment:
   ```bash
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations:
   ```bash
   python manage.py migrate
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Usage

- Access the admin at http://127.0.0.1:8000/admin/
- Create posts via the admin interface.

## Troubleshooting

- If you encounter database issues, delete db.sqlite3 and run migrations again.
- Ensure Python 3.8+ is installed.