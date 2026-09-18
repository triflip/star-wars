# 🌌 Star Wars Project - IT Academy

This is a React application that consumes the Star Wars API (SWAPI), allowing users to explore the saga's starships, view their details, and manage access through an authentication system.

## 🚀 Demo
You can see the application in action here: [https://triflip.github.io/star-wars/]

---

## 🛠️ Technologies Used

- **React** + **Vite** (Frontend)
- **Redux Toolkit** (Global state management)
- **React Router Dom** (Navigation and protected routes)
- **Firebase** (Authentication and persistence)
- **Styled Components** (Styling)
- **Jest** & **React Testing Library** (Test suite)

---

## 🧪 Testing

A testing architecture has been implemented to ensure code stability:

- **Unit Testing**: Custom Hook tests (`useAuthListener`).
- **Component Testing**: Rendering and interaction validation (`StarshipCard`).
- **Integration Testing**: Security flow verification (`ProtectedRoute`).

To run the tests:
```bash
npm  test 

---

## 📦 Local Installation 
1- Clone the repository: git clone https://github.com/usuari/Star-Wars.git 
2-Install the dependencies: npm install 
3-Create a .env file with your Firebase keys. 
4-Run the project: npm ru🌌 Star Wars Project – IT Academy
React application that interacts with the Star Wars API (SWAPI), allowing users to explore starships, view detailed information, and access the platform through a secure authentication system powered by Firebase.

🚀 Demo
Live version available at:
https://triflip.github.io/Star-Wars/

🛠️ Technologies Used
React + Vite – Fast and modern frontend tooling

Redux Toolkit – Global state management

React Router DOM – Navigation and protected routes

Firebase Authentication – Login, logout, and session persistence

TailwindCSS – Styling and responsive design

Jest + React Testing Library – Unit, component, and integration tests

✨ Features
Browse a list of Star Wars starships

View detailed information for each starship

User authentication (login/logout)

Protected routes for restricted content

Fully responsive UI (desktop & mobile)

Deployed on GitHub Pages with correct BASE_URL handling

🧪 Testing
The project includes a testing architecture to ensure stability and reliability:

Unit Tests  
Custom hook testing (useAuthListener)

Component Tests  
Rendering and interaction validation (StarshipCard)

Integration Tests  
Authentication flow and protected routes (ProtectedRoute)

Run the test suite:

bash
npm test
📦 Local Installation
Clone the repository

bash
git clone https://github.com/usuari/Star-Wars.git
Install dependencies

bash
npm install
Create a .env file with your Firebase configuration:

Codi
VITE_FIREBASE_API_KEY=xxxx
VITE_FIREBASE_AUTH_DOMAIN=xxxx
VITE_FIREBASE_PROJECT_ID=xxxx
VITE_FIREBASE_STORAGE_BUCKET=xxxx
VITE_FIREBASE_MESSAGING_SENDER_ID=xxxx
VITE_FIREBASE_APP_ID=xxxx
Run the development server

bash
npm run dev
📁 Project Structure 

src/
 ├── components/
 ├── features/
 ├── hooks/
 ├── pages/
 ├── router/
 ├── firebase/
 └── styles/
public/
 ├── logo/
 ├── logo_mobile/
 ├── social-icons/
 └── background/
📤 Deployment
The project is deployed using GitHub Pages and Vite’s BASE_URL configuration.

To deploy:

bash
npm run build
npm run deployn dev
