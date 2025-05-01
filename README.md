# WIZARDS Team Member Management System

A full-stack web application for managing team members with a modern, responsive interface. Built using the MERN stack (MongoDB, Express.js, React.js, and Node.js).

## 🌟 Features

- **Modern UI/UX**: Clean and responsive design with smooth transitions and animations
- **Member Management**: Add, view, update, and delete team members
- **Profile Images**: Upload and manage member profile images
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Real-time Validation**: Form validation and error handling
- **Modern Stack**: Built with the latest versions of React, Node.js, and MongoDB

## 🔧 Technologies Used

### Frontend
- React.js 18.2.0
- React Router DOM 6.10.0
- Axios for API requests
- Bootstrap 5.2.3 for styling
- CSS3 with custom variables and modern features
- Font Awesome for icons

### Backend
- Node.js with Express.js 5.1.0
- MongoDB with Mongoose 8.14.1
- Multer for file uploads
- CORS for cross-origin requests
- dotenv for environment variables

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local installation or Atlas URI)
- Git

### Installation

1. Clone the repository
```bash
git clone https://github.com/Vignesh-Rathnakumar/Wizards_FSD_CT2.git
cd Wizards_FSD_CT2
```

2. Install Backend Dependencies
```bash
cd backend
npm install
```

3. Configure Environment Variables
Create a .env file in the backend directory:
```env
PORT=5001
MONGO_URI=mongodb://127.0.0.1:27017/team_member_test
```

4. Install Frontend Dependencies
```bash
cd ../frontend
npm install
```

### Running the Application

1. Start the Backend Server
```bash
cd backend
npm run dev
```

2. Start the Frontend Development Server
```bash
cd frontend
npm start
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5001

## 📝 API Endpoints

### Members API
- `GET /api/members` - Get all team members
- `GET /api/members/:id` - Get a specific team member
- `POST /api/members` - Create a new team member
- `PUT /api/members/:id` - Update a team member
- `DELETE /api/members/:id` - Delete a team member

## 📁 Project Structure

```
├── backend/
│   ├── controllers/    # Route controllers
│   ├── models/        # MongoDB models
│   ├── routes/        # API routes
│   ├── uploads/       # Uploaded images
│   └── server.js      # Main server file
├── frontend/
│   ├── public/        # Static files
│   └── src/
│       ├── components/# React components
│       ├── pages/     # Page components
│       └── App.js     # Main React component
```

## 🎨 Features

### Member Management
- Add new team members with profile images
- View all team members in a responsive grid
- View detailed member information
- Update member details
- Delete members

### User Interface
- Modern and clean design
- Responsive layout for all screen sizes
- Loading states and error handling
- Form validation
- Image upload preview

## 🔒 Security Features

- Input validation and sanitization
- File upload restrictions (image files only)
- File size limits
- CORS configuration
- Error handling

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 👥 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 🔨 Built With Love by WIZARDS Team

For questions and support, please reach out to the team.