
## Signup  
- **Deadline**: [Add signup deadline, e.g., "DD/MM/YYYY"]  
- **Method**: Online form (link)  
- **Required Info**: Name, email, GitHub username, prior coding experience (if any).  

---

## Define Teams and Mentors  
- **Team Size**: 3–4 members.  
- **Mentor Allocation**: 1 mentor per 2 teams.  
- **Criteria**: Mix skill levels (beginners + intermediates).  
- **Mentor Roles**: Code reviews, weekly check-ins, debugging support.  

---

## First Content: Linux Handbook  
**Properties**  
- **Title**: Linux Basics & Environment Setup  
- **Deadline**: 3 days after publish date.  
- **Publish Day**: [Start date, e.g., "DD/MM/YYYY"]  
- **Participants**: All registered students.  
- **Required Contents**:  
  - Dual-boot installation guide (Ubuntu).  
  - Virtual Machine setup (VirtualBox/VMware).  
  - Terminal basics: `cd`, `ls`, `mkdir`, `grep`, `chmod`.  
  - File system navigation (`/home`, `/var`, `/etc`).  
- **Notes**: Provide troubleshooting tips for common installation errors.  

---

## First Section: Introduction  
**Properties**  
- **Title**: Introduction to Web Development  
- **Deadline**: Complete before Project 1 starts.  
- **Teachers**: [Instructor Name(s)]  
- **Place**: Online (Zoom/Google Meet).  
- **Considerations**:  
  - Assume no prior web development knowledge.  
  - Ensure students have installed VS Code, Git, and Python.  
- **Required Contents**:  
  - Web servers vs. web apps (with examples like Apache, Django).  
  - Course roadmap: Frontend/backend basics, Django, final project.  
- **Notes**: Record the session for later review.  
- **Slides**: Include diagrams of client-server architecture.  
- Post-Section Contents
  - GitHub Personal Site
---
## Project 1  
**Properties**  
- **Title**: Personal GitHub Portfolio  
- **Deadline**: 5 days after First Section.  
- **Required Contents**:  
  - Create a GitHub account (if missing).  
  - Build a repository with:  
    - A `README.md` introducing yourself.  
    - A Python script (e.g., "Hello World" or simple calculator).  
  - Push code using Git commands or VS Code extensions.  

**Description**  
- Practice version control basics and prepare for collaborative work in later projects.  

---

## Second Section: Python Refresher  
**Properties**  
- **Title**: Python Crash Course for Django  
- **Deadline**: 1 week after the live session.  
- **Teachers**: [Instructor Name(s)]  
- **Place**: Online (Interactive coding session).  
- **Considerations**:  
  - Use Python 3.10+.  
  - Ensure students have activated virtual environments.  
- **Required Contents**:  
  - Python syntax, data structures, OOP, modules.  
  - Code-along exercises (e.g., Task Manager CLI).  
- **Notes**: Provide cheat sheets for Python↔Django mappings (e.g., classes → models).  
- **Slides**: Link Python concepts to Django (e.g., functions → views).  

---

## Exercises & Homework  
**Collaborative Day**: Schedule a 2-hour live coding session for:  
- Debugging the Number Guessing Game (validate inputs, add hints).  
- Extending the Task Manager CLI with file I/O (JSON).  

**Structured Exercises**:  
1. **Number Guessing Game**
   - Write a script where the user guesses a random number (1–20).
   - Use `if/else` to give hints ("Too high!", "Too low!").
   - Track the number of attempts with a loop.
   - **Task**: Modify the game to accept only valid integers (handle invalid inputs).

3. **Task Manager CLI**
   - Use a dictionary to store tasks (keys: IDs, values: task descriptions).
   - Write functions to:
        - Add/remove tasks.
        - List all tasks.
        - Search tasks by keyword.
   - **Extra**: Refactor the code to use **list comprehensions** for filtering/searching tasks.
   - **Extra**: Refactor the code to use classes instead of dictionary.
   - **Extra**: Refactor the code to save the tasks in a file with functions in helper module
 
5. **Blog System with Classes**  
   - Create `Post` and `Comment` classes.
   - `Post` attributes: `title`, `content`, `author`, `comments` (list of `Comment` objects).
   - Save/load posts to a file (JSON or text).
   - Add exception handling for invalid data.
   - **Extra**: Add a decorator `@log_activity` to log when a post is created/edited.
   - **Extra**: call an api to create some instance of class and show them with `__str__`
---

