# Library Catalog System More

change the [[Library Catalog System]] 
_Task_: Allow users to "borrow" books (add `Borrower` field linked to `User`).

**Objective**: Manage books and authors.  
**Tasks**:
1. Create models:
    - `Author` (name, birth_date, bio).
    - `Book` (title, author [ForeignKey], publish_date, genre).
2. **Admin**:
    - Register both models.
    - Add a filter for books by genre in the admin panel.
3. **Templates**:
    - Create a page listing all authors.
    - For each author, display their books in a nested list.
    - allow users to borrow books.
4. **Queries**:
    - Find all books published after 2000.
    - Group books by genre.
