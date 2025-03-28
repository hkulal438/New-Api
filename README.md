Login Userlist Project
📌 Overview
This project is a user authentication system built with React, React Router, and TypeScript. It includes a login form that validates user credentials and redirects authenticated users to the user list page.
🚀 Features

User authentication with API integration

Smooth animations and transitions

Loading state management

Form validation with error handling

Protected routes with React Router

🛠️ Setup Instructions

1️⃣ Clone the Repository

git clone https://github.com/yourusername/login-userlist.git
cd login-userlist

2️⃣ Install Dependencies

Make sure you have Node.js (v16 or higher) installed, then run:

npm install

3️⃣ Start the Development Server

Run the following command to start the project:

npm run dev

The app will be available at: http://localhost:5173 (or the port specified by Vite).

4️⃣ Environment Variables (Optional)

If your project requires API keys or environment-specific configurations, create a .env file in the root directory and add:

VITE_API_URL=http://your-api-url

Replace http://your-api-url with your actual API endpoint.

🔧 API Integration

This project connects to an authentication API for login validation. Ensure the API is running before testing authentication.

🔹 Expected API Endpoints

POST /login → Accepts { email, password } and returns a JWT token.

GET /users → Fetches the list of users (requires authentication).

📌 Assumptions & Considerations

Authentication: Uses JWT for authentication and stores the token in localStorage.

Form Validation: Ensures both email and password are entered before submission.

Loading States: Shows a loader while authentication is in progress.

Error Handling: Displays appropriate messages for invalid credentials or API failures.

🏗️ Tech Stack

Frontend: React + Vite + TypeScript

State Management: React Hooks

Styling: Tailwind CSS

Notifications: react-hot-toast

Routing: React Router

API Calls: Axios

📜 License

This project is licensed under the MIT License. Feel free to modify and use it as needed.

✨ Contributors

Developed by Hrithika. Contributions are welcome!

If you have any issues or suggestions, feel free to open an issue or submit a pull request.

📞 Contact

For any queries, reach out via email at your-email@example.com.
Deploy Link:
https://employwise-api-45lg.vercel.app/

