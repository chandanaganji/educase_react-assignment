 PopX Landing React App
A pixel-perfect React.js application based on an Adobe XD design, featuring smooth navigation between screens (Landing, Signup, Login, and Profile). Built using React, CSS, and React Router DOM.

📌 Features
🔹 Pixel-perfect responsive layout

🔹 Navigation:

Signup → Login → Profile
🔹 Static profile page UI based on design

🔹 Clean CSS (no Tailwind used)

🔹 No external state management or backend

🛠️ Tech Stack
React.js
React Router DOM
CSS
📁 Folder Structure
popx-landing/
│
├── public/
│   └── index.html
│
├── src/
│   ├── components/
│   │   ├── Landing.jsx
│   │   ├── Signup.jsx
│   │   ├── Login.jsx
│   │   └── Profile.jsx
│   │
│   ├── styles/
│   │   ├── Landing.css
│   │   ├── Signup.css
│   │   ├── Login.css
│   │   └── Profile.css
│   │
│   ├── App.js
│   └── index.js
│
├── package.json
└── README.md
🚀 How to Run the Project
Clone the repository:

https://github.com/chandanaganji/educase_react-assignment
cd my-react-app
Install dependencies:

npm install
Start the development server:

npm start
View in browser:

http://localhost:3000
🔗 Page Flow
Landing Page (/) → Click Create Account → navigates to /signup → Click Already Registered? Login → navigates to /login

Signup Page (/signup) → On submit → navigates to /login

Login Page (/login) → On successful login → navigates to /profile

Profile Page (/profile) → Static design with Account Settings and user info

📸 Adobe XD Design Reference
Used reference screens from Adobe XD for pixel-perfect implementation.

📦 Dependencies
npm install react-router-dom
