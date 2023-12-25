# Husky Events Admin Dashboard

Welcome to the Husky Events Admin Dashboard! This web application is designed for administrators to manage events, users, and transactions related to Husky Events. The dashboard features a sleek and user-friendly interface with both dark mode and light mode options.

## Features

### Authentication

- **Admin Login:** Only administrators can log in to the dashboard to access its features.
- **Secure Authentication:** The application uses JSON Web Tokens (JWT) for secure session management.

### Dashboard Overview

- **Analytics:** View analytics and information about transactions, users, and events at a glance.
- **Dark Mode/Light Mode:** Switch between dark mode and light mode for a personalized user experience.

### Users and Events Management

- **CRUD Operations:** Administrators can perform Create, Read, Update, and Delete operations on both users and events.
- **Search Functionality:** Easily search for users or events based on specific criteria.
- **Pagination:** Navigate through large sets of data with pagination functionality.

## Preview the application

  The application has been deployed to the given link: https://husky-admin.onrender.com/

  **Log In Page**
<img width="1280" alt="Screenshot 2023-12-25 at 3 50 12 PM" src="https://github.com/atharvakonge/Netflix/assets/73238261/ed05b2e8-7227-4609-9994-fec096aed6d2">


  **Dashboard**
<img width="1261" alt="Screenshot 2023-12-25 at 3 53 27 PM" src="https://github.com/atharvakonge/Netflix/assets/73238261/0d82093b-35b4-4d91-a566-5c5768e00637">


  **Users Page**
  <img width="1269" alt="Screenshot 2023-12-25 at 3 53 41 PM" src="https://github.com/atharvakonge/Netflix/assets/73238261/3e63a044-3d5f-4f12-a8b2-06119385bdc0">


  **Events Page**
<img width="1265" alt="Screenshot 2023-12-25 at 3 54 23 PM" src="https://github.com/atharvakonge/Netflix/assets/73238261/89f0a779-7683-40f5-8f41-4efd38797801">


  **Light Mode**
<img width="1269" alt="Screenshot 2023-12-25 at 3 54 39 PM" src="https://github.com/atharvakonge/Netflix/assets/73238261/7115158b-dacd-45de-a3b6-1c068b430bcf">



## Technology Used

- **Frontend:**
  - React.js
  - Context API for state management
  - CSS for styling

- **Backend:**
  - Node.js
  - Express
  - MongoDB for database storage
  - JSON Web Token (JWT) for authorization and session management

## Setup Instructions

1. **Clone the repository:**
   - `git clone https://github.com/your-username/husky-events-admin-dashboard.git`
   - `cd husky-events-admin-dashboard`

2. **Install dependencies:**
   - `npm install`

3. **Set up your MongoDB database:**
   - Create a .env file in the server directory.
   - Add your MongoDB connection string:
     - `MONGODB_URI=your-mongodb-connection-string`

4. **Run the application:**
   - `npm start`

5. **Open Application in Browser:**
   - Open your browser and navigate to http://localhost:3000 to use the Husky Events Admin Dashboard.

## Contributing

Contributions to this project are welcome! Follow the steps below:

1. **Fork the repository on GitHub.**
2. **Create a new branch for your feature or bug fix:**
   - `git checkout -b feature-name`
3. **Make your changes and commit them:**
   - `git commit -m 'Add a new feature'`
4. **Push your changes to your fork:**
   - `git push origin feature-name`
5. **Submit a pull request through GitHub.**

## Issues

If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub repository.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.
