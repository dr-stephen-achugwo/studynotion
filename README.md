# StudyNotion

## Overview

StudyNotion is a full-fledged Ed-Tech platform built using the MERN stack. It provides a seamless experience for students and instructors, enabling efficient course management, interactive learning, and smooth user interactions.

## Features

- **User Authentication**: Secure login and registration system with JWT authentication.
- **Role-Based Access**: Different functionalities for students, instructors, and admins.
- **Course Management**: Instructors can create, edit, and manage courses.
- **Payment Integration**: Secure transactions using Stripe.
- **Interactive Dashboard**: Real-time progress tracking and insights.
- **Video Content Support**: Embedded video lectures and resources.
- **User Reviews & Ratings**: Students can rate and review courses.
- **Announcements & Notifications**: Instructors can send updates to students.
- **Responsive UI**: Fully optimized for mobile and desktop devices.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Gateway**: Stripe
- **Hosting**: Render (Backend), Vercel (Frontend)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/21BCS114140/StudyNotion.git
   ```
2. Navigate to the project folder:
   ```sh
   cd StudyNotion
   ```
3. Install dependencies for both frontend and backend:
   ```sh
   cd src && npm install
   cd ../server && npm install
   ```
4. Set up environment variables (`.env` files for backend and frontend):
   - Create `.env` file in the backend directory with the following:
     ```
     MAIL_HOST = smtp.yourmailprovider.com
     MAIL_USER = your-email@example.com
     MAIL_PASS = your-email-password

     JWT_SECRET = your-jwt-secret
     FOLDER_NAME = your-folder-name

     RAZORPAY_KEY = your-razorpay-key
     RAZORPAY_SECRET = your-razorpay-secret

     CLOUD_NAME = your-cloudinary-name
     API_KEY = your-cloudinary-api-key
     API_SECRET = your-cloudinary-api-secret

     MONGODB_URL = your-mongodb-url
     PORT = 4000
     ```
   - For frontend, update `.env` with:
     ```
     REACT_APP_API_URL = your_backend_url
     ```
5. Start the development servers:
   ```sh
   cd server && npm run dev
   cd src && npm start
   ```

## Deployment

- **Frontend**: Deployed on Vercel
- **Backend**: Deployed on Render

## Contributing

Contributions are welcome! If you’d like to contribute:

1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit your changes
4. Push the branch and create a pull request

## License

This project is licensed under the MIT License.

## Contact

For any inquiries, contact:

- **Email**: gauravb965516@gmail.com
- **GitHub**: [https://github.com/21BCS11410/](https://github.com/21BCS11410/)
- **Live Demo**: [https://study-notion-final-rho.vercel.app/](https://study-notion-final-rho.vercel.app/)


