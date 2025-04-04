# Library Catalog System  

## **Objective**  
Build a system to manage books and authors, allowing users to borrow books.  

## **Tasks**  

### **1. Create Models**  
   - **`Author`**:  
     - `name` (str)  
     - `birth_date` (date)  
     - `bio` (text)  
   - **`Book`**:  
     - `title` (str)  
     - `author` (ForeignKey to `Author`)  
     - `publish_date` (date)  
     - `genre` (choice field or char field)  
     - **New Feature**: `borrower` (ForeignKey to `User`, can be `null` when available)  

### **2. Admin Panel**  
   - Register `Author` and `Book` models.  
   - Add a **filter for books by genre** in the admin panel.  

### **3. Templates & Views**  
   - Create a page listing **all authors**.  
   - For each author, display a **nested list of their books**.  
   - Allow users to **borrow books** (update `borrower` field).  

### **4. Queries**  
   - Find **all books published after 2000**.  
   - Group books by **genre**.  

This project will help you practice **Django models, relationships, admin customization, queries, and templates**. 🚀  
