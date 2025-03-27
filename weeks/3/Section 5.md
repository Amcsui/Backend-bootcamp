# Fifth Section: Auth & Test

**Properties**
- Title: Authentication & Testing in Django
- Teachers: [Names]
- Place: Online/In-Person
- Considerations: Code-along format. shared code base
---
**Content Structure**
1. Users & Authentication [20 min]
	- Users [5 min] : Default `User` model, `create_user()`, `create_superuser()`, `request.user`.
	- Custom User Model [10 min]: Extend `AbstractUser` (e.g., add `bio` field).
	- Groups & Permissions [3 min]: Demo creating groups (e.g., "Authors", "Editors").
	- Access Control [2 min]: `@login_required`, `@permission_required`.
2. Admin Panel [20 min]
	- Customizing Admin [15 min]:
	    - `list_display`, `search_fields`, `list_filter`.
	    - Override `admin_template` (simple example).
	- Admin Actions [5 min]: Add a "publish selected posts" action.
3. Testing [30 min]
	- Writing Tests:
	    - Model tests (e.g., `User` creation).
	    - View tests (e.g., login redirects).
	    - Test client (`client.post()` for forms).

---
 **Resources**
- [Django Authentication Docs](https://docs.djangoproject.com/en/4.2/topics/auth/)
- [Testing in Django](https://docs.djangoproject.com/en/4.2/topics/testing/)
- [Admin Customization Guide](https://realpython.com/customize-django-admin-python/

---
**after course content**:
- github action for automated testing