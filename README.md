# Frontend Case Study  

## Overview  
This web application is built using the MERN stack, offering user authentication, profile management, dynamic mapping, and an admin panel for managing user roles and profiles.  

## Key Features  

### Backend Features  
- **User Management:**  
  - Register, login, and update user accounts.  
  - Role-based access (Admin/User).  
  - Admin can view and manage user roles.  

- **Profile Management:**  
  - CRUD operations for profiles (Admin-only).  
  - Filter profiles by city, state, and country.  
  - Pagination and search functionality.  

- **File Upload:**  
  - Upload profile pictures using **Multer** and **Cloudinary**.  

### Technologies Used (Backend):  
- **Backend:** Node.js, Express.js, MongoDB.  
- **Authentication:** JWT-based user authentication and role authorization.  
- **Middleware:**  
  - Authentication and authorization (`authenticateUser`, `authorizeUser`).  
  - File uploads using Multer and Cloudinary.  
  - Validation with Express-validator.  

---

### Frontend Features  
- **Authentication with Context API & Reducer:**  
  - `AuthContext` handles user authentication and provides user state across the app.  
  - Private routes (`PrivateRoute`) restrict access to specific pages based on roles.  

- **Admin Panel:**  
  - Manage user profiles with **CRUD operations** (create, read, update, delete).  
  - Uses **MUI components** for a clean and responsive UI.  

- **Registration and Login:**  
  - Registration and Login components include **form validations** and server-side error handling.  
  - Notifications are displayed using **react-toastify**.  

- **Redux for Profile Management:**  
  - Profiles are managed using Redux (actions, reducers, store) to ensure state consistency across the app.  

- **Map Integration:**  
  - **MapComponent** integrates **react-leaflet** for displaying map views of user locations.  

- **Routing with React Router:**  
  - Dynamic routing for user and admin-specific pages.  
  - Admin-specific routes are conditionally rendered based on user roles.  

- **Toast Notifications:**  
  - Feedback is displayed for registration and login actions.  

- **Modern UI:**  
  - Leverages **Material-UI (MUI)** for consistent and professional UI components.  

### Technologies Used (Frontend):  
- **Frontend:** React.js, Redux, Material-UI.  
- **Map Integration:** React-Leaflet.  
- **State Management:** Redux and Context API.  
- **Routing:** React Router.  

---

## Installation  

### Backend Setup  
1. Clone the repository:  
   ```bash
   git clone <repository-url>
   cd backend
