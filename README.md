# Job Portal

A full-stack job portal application built with React.js, Node.js, and MongoDB, featuring user authentication, job posting, and application management.

## Features

- 🔐 User Authentication (Login/Signup)
- 👥 User Profile Management
- 💼 Job Posting and Management
- 🏢 Company Profile Management
- 📝 Job Application System
- 🔍 Job Search and Filtering
- 📊 Admin Dashboard
- 🎯 Latest Job Listings
- 📱 Responsive Design

## Tech Stack

### Frontend
- React.js
- Redux for state management
- Tailwind CSS for styling
- Vite as build tool

### Backend
- Node.js
- Express.js
- MongoDB
- Cloudinary for file storage

## Getting Started

### Prerequisites
- Node.js
- MongoDB
- npm/yarn

### Installation

1. Clone the repository
```bash
git clone [repository-url]
cd job_portal-main
```

2. Install Backend Dependencies
```bash
cd backend
npm install
```

3. Install Frontend Dependencies
```bash
cd frontend
npm install
```

### Configuration

1. Backend Configuration
Create a `.env` file in the backend directory with the following variables:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

2. Frontend Configuration
Create a `.env` file in the frontend directory:
```
VITE_API_URL=http://localhost:5000
```

### Running the Application

1. Start the Backend Server
```bash
cd backend
npm start
```

2. Start the Frontend Development Server
```bash
cd frontend
npm run dev
```

## Project Structure

### Frontend
- `/src/components` - React components
- `/src/redux` - Redux store and slices
- `/src/hooks` - Custom React hooks
- `/src/utils` - Utility functions

### Backend
- `/controllers` - Request handlers
- `/models` - Database models
- `/routes` - API routes
- `/middlewares` - Custom middleware functions
- `/utils` - Utility functions

## Features Breakdown

### User Features
- User registration and authentication
- Profile creation and management
- Job search and filtering
- Job application submission
- Track applied jobs

### Company Features
- Company profile management
- Post and manage job listings
- View and manage applicants
- Company dashboard

### Admin Features
- Manage all job listings
- Manage companies
- View all applicants
- System administration

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Acknowledgments

- React.js community
- Node.js community
- MongoDB
- Cloudinary
- All contributors and supporters
