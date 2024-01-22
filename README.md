## Project Name: Leo's Tweet

### Introduction
"Leo's Tweet" is a web-based application that emulates key features of Twitter, allowing users to share updates, interact with posts, and connect with others. It's designed with a responsive user interface and provides a comprehensive user experience with both front-end and back-end functionalities.

### Features
- **User Authentication:** Secure login, registration, and session management using JWT (JSON Web Tokens).
- **Personalized User Profiles:** Users can create and update profiles, including profile pictures and personal information.
- **Posting:** Users can post comments and view posts from other users.
- **Post Interactions:** Users can like posts in various forms (heart, star, thumbs up) and view post statistics.
- **Responsive Design:** The application is fully responsive, with a custom CSS file for consistent styling across devices.
- **Social Media Integration:** Open Graph tags for enhanced link sharing on social media platforms.
- **Backend Functionality:** Flask-based server handling user authentication, profile updates, posting, and retrieving posts.

### Technology Stack
- **Frontend:** HTML, CSS (custom styles in `mystyle.css`), JavaScript (jQuery for AJAX calls and DOM manipulation).
- **Backend:** Python (Flask), MongoDB (via pymongo for database interactions), JWT for authentication.
- **Database:** MongoDB for storing user data, posts, and interaction data.

### Setup and Installation
1. **Clone the Repository:** Get a copy of the project from the repository.
2. **Install Dependencies:** Install necessary Python packages, including Flask, pymongo, and PyJWT, and set up MongoDB.
3. **Configure Database:** Set up MongoDB with appropriate user credentials and database name (`dbsparta_plus_week4`).
4. **Environment Variables:** Set the secret key for JWT and configure any other environment-specific variables.
5. **Running the Application:**
   - Start the Flask server by running `app.py`.
   - Access the application via a web browser, pointed to `localhost:5000` or the configured port.

### Usage
- **Register/Login:** Users can register a new account or log in to an existing account.
- **Profile Management:** Users can update their profile information and upload profile pictures.
- **Posting and Interacting:** Users can create new posts, view others' posts, and interact with them through likes.
