# Fourth Section: Database

**Properties**
  - Title: Database
  - Teachers: [Names]
  - Place: Online/In-Person
  - Considerations: Code-along format.

---
**Content Structure**

1. Database & SQL [45 min]
	- Understand Databases & DBMS [10 min] :
	    - Relational vs. NoSQL, tables, schemas.
	- SQL CLI  [20 min] :
	    - Basic commands: `CREATE TABLE`, `INSERT`, `SELECT`, `WHERE`, `JOIN`.
	    - Demo: Build a `flights` table with `flight_id`, `origin`, `destination`, `duration`.
	- SQL in Python [15 min] :
	    - Use `sqlite3` module to execute queries in a script.
2. Django Models
	- Creating Models & Django ORM [45 min] :
	    - Define `Flight` and `Airport` models (e.g., `Flight` has a foreign key to `Airport`).
	    - Migrations: `makemigrations`, `migrate`.
	- Admin Panel [30 min] :
	    - Create a superuser.
	    - Register models in `admin.py`.
	    - Filter/search flights in the admin.
	- Django Shell Queries [30 min] :
	    - CRUD operations: `Flight.objects.create()`, `.filter()`, `.get()`, `.delete()`.
	    - Complex queries: `exclude()`, `Q` objects, aggregations.
3. Flight Project [90 min] :
	- Build a basic flight booking system:
	    - List all flights (template loops).
	    - Detail page for a flight (dynamic URL).
	    - Form to "book" a flight (hardcoded user for now).