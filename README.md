# Quiz-backend
This repository contains the backend code for a quiz application, providing the core functionality to manage quizzes, user authentication, and scoring.

**Features**\n
User Authentication: Users can sign up, log in, and securely access the quiz functionalities.
Quiz Management: Administrators can create, modify, and retrieve quizzes, including adding or removing questions.
Quiz Taking: Users can take quizzes, answer questions, and receive instant feedback on their performance.
Score Tracking: The backend tracks user scores for completed quizzes, providing insights into past quiz attempts and rankings.

**Technologies Used**
Node.js: Backend server environment.
MySQL: SQL database for storing user profiles, quiz questions, answers, and scores.

**API Endpoints**
POST /api/auth/signup: Register a new user.
POST /api/auth/login: Log in an existing user.
GET /api/quizzes: Get a list of available quizzes.
GET /api/quizzes/:id: Get details of a specific quiz.
POST /api/quizzes: Create a new quiz.
PUT /api/quizzes/:id: Update an existing quiz.
DELETE /api/quizzes/:id: Delete a quiz.
POST /api/quizzes/:id/take: Take a quiz.
GET /api/scores: Get user scores.
GET /api/scores/:userId: Get scores of a specific user.

**Contribution**
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.


