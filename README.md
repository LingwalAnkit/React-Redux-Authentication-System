# Secure Authentication System with React & Redux

A modern, secure authentication system built with React, Redux Toolkit, and Node.js. Features a clean, responsive UI with Ant Design components and comprehensive state management.

## 🚀 Features

- **User Authentication**
  - Secure login and registration
  - JWT-based authentication
  - Password hashing with bcrypt
  - Form validation and error handling

- **Modern UI/UX**
  - Clean and responsive design
  - Interactive form feedback
  - Success/error notifications
  - Loading states and animations

- **State Management**
  - Centralized state with Redux Toolkit
  - Persistent authentication
  - Protected routes
  - Efficient error handling

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit
- React Router DOM
- Ant Design
- Axios
- TailwindCSS

### Backend
- Node.js
- Express.js
- MongoDB
- JWT
- Bcrypt

## 📦 Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/auth-system.git
cd auth-system
```

2. Install dependencies for both frontend and backend
```bash
# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install
```

3. Set up environment variables
```bash
# In server directory, create a .env file
PORT=3000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

4. Start the development servers
```bash
# Start backend server
cd server
npm start

# Start frontend development server
cd client
npm start
```

## 🔧 Configuration

### Frontend Configuration
- Update the API URL in `src/features/auth/authActions.js`
- Modify the token storage mechanism in `src/features/auth/authSlice.js`
- Adjust the route protection logic in `src/components/PrivateRoute.jsx`

### Backend Configuration
- Configure MongoDB connection in `server/Database/MongoDB.js`
- Modify JWT settings in `server/Controller/AuthController.js`
- Adjust CORS settings in `server/index.js`

## 📱 Usage

1. Register a new account
   - Navigate to the registration page
   - Fill in required details
   - Submit the form

2. Login to your account
   - Enter your credentials
   - Access the dashboard

3. Protected Routes
   - Authenticated users can access the dashboard
   - Non-authenticated users are redirected to login

## 🔒 Security Features

- Password hashing using bcrypt
- JWT-based authentication
- Protected routes
- Form validation
- Error handling
- XSS protection
- CORS configuration

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 👤 Author

Your Name
- GitHub: [@LingwalAnkit](https://github.com/LingwalAnkit)
- LinkedIn: [Ankit Lingwal](https://www.linkedin.com/in/ankit-lingwal-9b18472aa/)

## 🙏 Acknowledgments

- Ant Design for the beautiful UI components
- Redux team for the amazing state management solution
- React Router team for the routing solution

## 📞 Support

For support, email ankit.10219051723@ipu.ac.in or create an issue in this repository.
