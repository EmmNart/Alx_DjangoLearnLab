# Django Admin Configuration for Book Model

## Steps
1. Registered the `Book` model in `admin.py`.
2. Customized admin list view with:
   - `list_display` → shows title, author, and publication_year.
   - `list_filter` → allows filtering by author and publication year.
   - `search_fields` → enables search by title and author.
   - `ordering` → sorts books by title.

## Verification
- Run the server: `python manage.py runserver`
- Access the admin at `http://127.0.0.1:8000/admin/`
- Log in with superuser account
- Navigate to **Books** → All books are now easily searchable, filterable, and sorted.
