# CLI Blog System

## **Overview**  
In this exercise, you will build a **command-line blog system** using Python classes. Users will be able to create blog posts, add comments, save and load posts from a file, and interact with the system via a CLI menu.

## **Structured Exercises**  

### **1. Define `Post` and `Comment` Classes**  
   - Create a `Post` class with attributes:  
     - `title` (str)  
     - `content` (str)  
     - `author` (str)  
     - `comments` (list of `Comment` objects)  
   - Create a `Comment` class with attributes:  
     - `author` (str)  
     - `content` (str)  

### **2. Implement Save and Load Functionality**  
   - Store posts in a **JSON or text file**.  
   - Implement functions to **save** and **load** posts.  
   - Ensure that data is correctly formatted when reading/writing files.  

### **3. Build a CLI Menu for User Interaction**  
   Users should be able to:  
   - **Create a new post** (ask for title, content, author).  
   - **View all posts** (display title, author, and comments).  
   - **Add a comment** to a post.  
   - **Delete a post** (optional).  
   - **Save and load posts** from a file.  

### **4. Handle Exceptions for Invalid Inputs**  
   - Prevent crashes when users enter incorrect input.  
   - Ensure that posts and comments are properly formatted.  

### **5. Extra Features (Optional)**  
   - **Logging with a Decorator**  
     - Create a `@log_activity` decorator to log when a post is created, edited, or deleted.  
   - **Fetch Sample Posts from an API**  
     - Call an API (e.g., `https://jsonplaceholder.typicode.com/posts`) to generate sample blog posts.  
     - Convert API data into `Post` instances and display them using `__str__`.  

This exercise will help you practice **OOP, file handling, CLI development, error management, decorators, and API integration**. 🚀  

