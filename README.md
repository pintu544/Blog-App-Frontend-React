## Blog App

### Frontend (React)

#### Authentication Flow:

1. **Sign up Page:**
   - Create a signup page with form validation using React state and controlled components.
   - Implement proper input validation logic.

2. **Login Page:**
   - Develop a login page with form validation and handle user authentication using JWT tokens.
   - Store authentication tokens in local storage or cookies for maintaining user sessions.

#### Protected Routes:

- Make blogs and the profile page private by implementing protected routes.

#### Blog Listing Page:

1. **Display Blogs:**
   - Implement a page to fetch and display all blogs from the backend using API calls.

2. **Filter Options:**
   - Provide filter options for categorizing blogs by category using dropdowns or tags.

#### Blog Detail Page:

- Create a page to display the full content of a single blog when clicked on from the blog listing page.

#### Profile Page:

1. **Profile Overview:**
   - Implement a profile page where writers can see all their blogs.

2. **CRUD Operations:**
   - Provide functionality to perform CRUD operations on blogs (create, read, update, delete).

#### Search Functionality:

- Add a search bar to search for blogs based on keywords.

### Backend (Node.js)

#### User Authentication:

1. **Signup and Login Endpoints:**
   - Set up API endpoints for user signup and login.
   - Use bcrypt to securely store passwords.

2. **JWT Integration:**
   - Utilize JSON Web Tokens (JWT) for managing user sessions and authentication.

#### Blog API Endpoints:

1. **Fetch Blogs:**
   - Create API endpoints for fetching all blogs and fetching a single blog by ID.

2. **CRUD Operations:**
   - Implement endpoints for creating a new blog, updating an existing blog, and deleting a blog.

3. **Authorization:**
   - Ensure that only the logged-in user can create, edit, and delete their blogs.

#### Database Integration:

- Connect the Node.js server to a database (e.g., MongoDB) and define models and schemas for users and blogs.

### Submission

1. **GitHub Link:**
   - Provide a link to the GitHub repository.

2. **Deployed App Link:**
   https://my-blog-app-testing.netlify.app/

3. **Video Presentation:**
   - Create a video showcasing the functionalities of the app.



