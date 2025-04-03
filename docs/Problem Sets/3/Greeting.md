###  Dynamic Routing

**Objective**: Master Django URL patterns and dynamic content.  
**Tasks**:
1. Add a route `/submit`
	- if `request.method == "POST"` redirect to  `/greet/{name}`
	-  if `request.method == "GET"` render html page with form 
2. Add a route `/greet/<str:name>` that displays "Hello, [name]!" using `HttpResponse`.
3. Create a template `greet.html` that styles the greeting with Bootstrap.
4. Modify the view to pass the `name` variable to the template.
5. **Challenge**: Add a dropdown in your contact form to select a title (Mr/Ms/Dr) and reflect it in the greeting.