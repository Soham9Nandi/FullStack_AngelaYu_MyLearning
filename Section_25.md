1. EJS, dynamic HTML
2. res.render instead of send or sendFile because it's a dynamic thing instead of a static thing
3. res.render("index.ejs",{var : value})
4. <%= name %>

   # FORM IN HTML
   1. form, attributes and methods, important, extremely

5. You can use ; to pass mmultiple CLI arguments in one line

# Different EJS tags
1. Variable -> <%= %>
2. Executable Code -> <% %> /// but no output will be shown, just executed, only the code is to be enclosed in tags, nothing else.
3. Rendering more HTML -> <%- %>
4. When you want to escape EJS -> <%% %%>
5. EJS Comment -> <%# %>
6. <%- include('ejs file') %>


6. what if there's no data being passed to the ejs from the backend?
We check with if condition and the data, but we can't write like, if fruits, we need to write if **locals.fruits**

7. Placeholder in forms
8. Puclic folder for holding static files and then asking express to use them while rendering data
9. a link is kind of like a get request

10. Use the static files with the use of app.use(express.static(folder address))
11. Also, the ejs is always found in reference to the views folder

# Project structure
1. Public for static files
2. views for ejs files
3. everything else outside
 
