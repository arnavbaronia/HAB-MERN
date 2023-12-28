# MERN Stack Healthcare Appointment System

This project is a Healthcare Appointment System built using the MERN stack (MongoDB, Express.js, React, and Node.js). It includes user authentication, different user roles, appointment booking functionality, an admin dashboard, and profile management.

## Features

### User Authentication:

- Patients, doctors, and administrators have unique login credentials.
- Secure authentication methods ensure data privacy.

### User Roles:

#### Patients:

- Can view available doctors.
- Schedule appointments.
- View appointment history.

#### Doctors:

- Manage their availability.
- View appointment details.
- Update patient records.

#### Administrators:

- Have access to system-wide functionalities.
- User management.
- Overall system configuration.

### Appointment Booking:

- Patients can search for available doctors based on their availability.
- Real-time calendar availability for doctors.
- Patients can book, reschedule, or cancel appointments.

### Admin Dashboard:

- Overview of system statistics, including the number of appointments.
- User management: add, edit, or remove users.
- System configuration settings.

### Profile Management:

- Patients and doctors can update their profiles.
- Includes personal information and medical history.
- Profile verification for doctors.

## MERN Stack Overview

- **MongoDB:**
  - NoSQL database used to store user information, appointment details, and system configurations.

- **Express.js:**
  - Backend framework for handling server-side logic and routing.

- **React:**
  - Frontend library for building user interfaces.

- **Node.js:**
  - JavaScript runtime for executing server-side code.

## Getting Started

Follow these steps to download and run the MERN stack project:

### How to Run

1. **Install Dependencies:**
   - Navigate to the server and client directories separately and run:
     ```bash
     cd server
     npm install
     ```

     ```bash
     cd client
     npm install
     ```

2. **Configure Environment Variables:**
   - Create a `.env` file in the `server` directory with the following content:
     ```makefile
     MONGO_URI=your_mongodb_connection_string
     SECRET_KEY=your_secret_key
     ```

3. **Run the Server:**
   - In the `server` directory, run:
     ```bash
     npm start
     ```

4. **Run the Client:**
   - In the `client` directory, run:
     ```bash
     npm start
     ```

5. **Access the Application:**
   - Open your browser and go to [http://localhost:3000](http://localhost:3000) to use the Healthcare Appointment System.

6. **Admin Dashboard:**
   - Access the admin dashboard at [http://localhost:3000/admin](http://localhost:3000/admin) and log in with administrator credentials.

## Connect with Arnav Baronia

- LinkedIn: [Arnav Baronia](https://www.linkedin.com/in/arnav-baronia-379b57234/)
- LeetCode: [Arnav Baronia](https://leetcode.com/arnavbaronia/)

## Clone the Repository:

```bash
git clone https://github.com/your-username/healthcare-appointment-system.git
cd healthcare-appointment-system
