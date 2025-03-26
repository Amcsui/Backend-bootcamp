
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
- **Notes**: add a link to this content notes later 

---

## First Section: Introduction  
**Properties**  
- **Title**: Introduction to Web Development  
- **Teachers**: [Instructor Name(s)]  
- **Place**: In-Person [place].  
- **Considerations**:  
  - Assume no prior web development knowledge.  
  - Ensure students have installed VS Code, Git, and Python.  
- **Required Contents**:  
  - Web servers vs. web apps (with examples like Apache, Django).  
  - Course roadmap: Frontend/backend basics, Django, final project.  
- **Notes**: Record the session for later review.  
- **Slides**: Include diagrams of client-server architecture.  
- **Post-Section Contents:**
  - GitHub Personal Site
- **exercise:** [[Problem Set 1]]

---

## Second Section: Python Refresher  
**Properties**  
- **Title**: Python Crash Course for Django  
- **Teachers**: [Instructor Name(s)]  
- **Place**: Online and In-Person [Unknonw].    
- **Required Contents**:  
  - Python syntax, data structures, OOP, modules.  
  - Code-along exercises (e.g., Task Manager CLI).
- **Notes**: Provide cheat sheets and Slides. and a note to read + videos.  
---
## Project 1  
**Collaborative Day**: Schedule a 2-hour live coding session for:  
- Debugging the Number Guessing Game (validate inputs, add hints).  
- Extending the Task Manager CLI with file I/O (JSON).  

**Structured Exercises**:  
1. **Number Guessing Game**
   - Write a script where the user guesses a random number (1–20).
   - Use `if/else` to give hints ("Too high!", "Too low!").
   - Track the number of attempts with a loop.
   - **Task**: Modify the game to accept only valid integers (handle invalid inputs).

2. **Task Manager CLI**
   - Use a dictionary to store tasks (keys: IDs, values: task descriptions).
   - Write functions to:
        - Add/remove tasks.
        - List all tasks.
        - Search tasks by keyword.
   - **Extra**: Refactor the code to use **list comprehensions** for filtering/searching tasks.
   - **Extra**: Refactor the code to use classes instead of dictionary.
   - **Extra**: Refactor the code to save the tasks in a file with functions in helper module
 
3. **Blog System with Classes**  
   - Create `Post` and `Comment` classes.
   - `Post` attributes: `title`, `content`, `author`, `comments` (list of `Comment` objects).
   - Save/load posts to a file (JSON or text).
   - Add exception handling for invalid data.
   - **Extra**: Add a decorator `@log_activity` to log when a post is created/edited.
   - **Extra**: call an api to create some instance of class and show them with `__str__`
---

