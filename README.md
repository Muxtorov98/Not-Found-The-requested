# Not-Found-The-requested
Not Found The requested URL was not found on this server.  Additionally, a 404 Not Found error was encountered while trying to use an ErrorDocument to handle the request.

![image](https://github.com/user-attachments/assets/b3b0e66d-8fb4-44ed-9d7f-c36d6c27972d)

.htaccess

Options -MultiViews
RewriteEngine On
RewriteCond %{REQUEST_FILENAME} !-f
RewriteRule ^ index.html [QSA,L]
