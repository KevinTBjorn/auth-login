# React Authentication with Token-Based System (Training Project)

This project is a training exercise designed to help me learn and implement authentication using a token-based system. The focus is on understanding how to manage user access between public and private pages.

## Learning Objectives
- **Mock API Integration**: Using a mock API to simulate user authentication by returning a user token.
- **Building a Login Page**: Develop a login page that fetches the token and manages user authentication within the app.
- **Exploring Token Storage**: Experiment with storing tokens in `localStorage` and `sessionStorage`, while understanding the security and user experience implications of each approach.
- **User Workflow Implementation**: Learn how to provide a smooth user experience by allowing users to log in and continue without being redirected to a dedicated login page.

This project is to learn web application security, and showcases my progress in building secure, user-friendly applications.

## How to Run the Application

Follow these steps to get the application up and running:

#### 1. **Clone the Repository**
```
   git clone https://github.com/your-username/react-auth-training.git
   cd react-auth-training
```
#### 2. **Install Dependencies**
```
npm install
```
#### 3. **Start the Development Server**
```
npm run dev
```
The application should now be running at http://localhost:3000/.

#### 4. **Testing Authentication**

- To test authentication with an already set token, modify UseToken.js.

- Change sessionStorage to localStorage in the file to observe the difference.

- Restart the application and verify how the token is stored and retrieved.
