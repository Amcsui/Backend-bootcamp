# **Third Section: Introduction to Web (Markup & Django)**  

**Properties**  
- **Title**: Web Basics with HTML, CSS, and Django  
- **Teachers**: [Names]  
- **Place**: Online/In-Person  
- **Considerations**:  
  - Prioritize hands-on coding (e.g., build a simple Django page during the session).  
  - Use a **pre-configured Django starter template** to save setup time.  
  - Share a GitHub repo with the starter Django project to avoid installation delays.  
---

**Content Structure**

1. What is Markup
2. HTML [45 min]
	- tags and elements
	- forms
3. CSS [15 min]
	- query selectors
		- id 
		- class
		- name
	- edit some styles
4. BootStrap [15 min]
5. Rest
6. Django
	- install and init a project [5 min]
	- Understanding the Django project structure (MVT pattern). [3 min]
	- Integrating Git into the Django workflow. [5 min]
	- Request and Response [15 min]
	- Routing [20 min]
	- Template and Template engine [15 min]


---



---

#### **Content Structure**  
**1. What is Markup?** [5–10 min]  
- Explain markup languages (HTML vs. Markdown) with examples.  

**2. HTML** [45 min]  
- **Tags/Elements**: `<html>`, `<head>`, `<body>`, `<h1>`, `<p>`, `<a>`, `<img>`.  
- **Forms**:  
  - `<form>`, `<input>`, `<textarea>`, `<button>`.  
  - Live demo: Build a contact form (no backend logic yet).  

**3. CSS** [15 min]  
- **Selectors**:  
  - `#id`, `.class`, `tag` (demo in-browser with DevTools).  
- **Inline Styles**: Change text color, padding, margin.  
- **Link CSS to HTML**: `<link rel="stylesheet">` (brief).  

**4. Bootstrap** [10 min]  
- **Quick Setup**: CDN link.  
- **Demo**: Use Bootstrap classes (`container`, `btn`, `card`) to style the contact form.  

**5. Rest** [10 min]  
- Q&A or troubleshooting.  

**6. Django**  
- **Install & Init Project** [5 min]:  
  - `django-admin startproject my_site` (use pre-installed virtual env).  
- **Django Project Structure (MVT)** [5 min]:  
  - Explain `settings.py`, `urls.py`, `views.py`.  
- **Git Integration** [5 min]:  
  - `git init`, add Django project, commit.  
- **Request & Response** [15 min]:  
  - Build a simple view (`def home(request): return HttpResponse("Hello")`).  
- **Routing** [20 min]:  
  - Map URLs to views in `urls.py` (include dynamic URLs like `/user/<str:name>`).  
- **Templates** [20 min]:  
  - Create `templates/` directory, render HTML with `render(request, 'index.html')`.  
  - Demo template variables (`{{ variable }}`).  
