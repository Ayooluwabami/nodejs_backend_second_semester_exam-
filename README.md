Blogging API
The Blogging API is a RESTful web service that provides endpoints for managing blogs and user authentication. It allows users to create, read, update, and delete blogs, as well as sign up and sign in to the application. The API is built using Node.js, Express.js, and MongoDB.

Features
User Management: Users can sign up and sign in to the application.
Blog Management: Users can create, read, update, and delete blogs.
Authentication: JWT is used for user authentication, with tokens expiring after one hour.
Blog States: Blogs can be in draft or published states.
Pagination: Paginated endpoints for fetching lists of blogs.
Search and Filtering: Search and filter blogs by author, title, and tags.
Sorting: Order blogs by read count, reading time, and timestamp.
Middleware Logging: Requests are logged using Winston middleware.
Error Handling: Middleware for handling errors and logging stack traces.

API Documentation
The API documentation is as follows:

User Routes:
POST /api/users/signup: Sign up a new user.

POST /api/users/signin: Sign in an existing user.


Blog Routes:
GET /api/blogs: Fetch a list of blogs.

GET /api/blogs/:id: Fetch a single blog by ID.

POST /api/blogs: Create a new blog.

PUT /api/blogs/:id: Update a blog by ID.

DELETE /api/blogs/:id: Delete a blog by ID.

GET /api/blogs/my-blogs: Fetch blogs authored by the current user.

Author
Ayobami Ekundayo
