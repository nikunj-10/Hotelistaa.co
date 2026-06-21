
# Hotel Booking Platform

A full-stack hotel booking platform that enables users to browse rooms, make reservations, and manage bookings through a real-time web application. The platform includes authentication, role-based access control, live booking synchronization, and administrative management features.



## Overview

This project was developed to simplify hotel reservation workflows while providing a seamless booking experience for customers and administrators.

The application uses Firebase services for authentication and real-time data synchronization, allowing booking updates to be reflected instantly without page refreshes.



## Features

### User Features

- User registration and authentication
- Google OAuth login
- Facebook OAuth login
- Browse available rooms
- Book hotel rooms
- View booking history
- Real-time booking status updates

### Admin Features

- Role-based access control (RBAC)
- Manage hotel bookings
- Accept or reject reservations
- Update booking statuses
- Monitor platform activity



## Technology Stack

| Layer | Technologies |
|---------|---------|
| Frontend | React, Material UI, Styled Components |
| State Management | Redux |
| Authentication | Firebase Authentication |
| Database | Firebase Realtime Database |
| Authorization | Role-Based Access Control (RBAC) |



## System Architecture

### Authentication

The platform supports multiple authentication methods:

- Email and Password
- Google OAuth
- Facebook OAuth

### Authorization

The system implements role-based access control:

- Customer
- Administrator

Administrative accounts are restricted from user-facing booking workflows.

### Real-Time Synchronization

Firebase Realtime Database is used to synchronize booking updates across users and administrators without requiring page refreshes.



## Core Functionalities

### Booking Management

- Create bookings
- Update bookings
- Cancel bookings
- Track booking status

### Room Filtering

Users can filter rooms based on:

- Room Type
- Price Range
- Availability

### State Management

Redux is used to manage:

- Room listings
- Search filters
- Booking data
- Application state



## Project Structure

```text
hotel-booking/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   ├── context/
│   ├── firebase/
│   └── App.js
├── package.json
└── README.md
````



## Getting Started

### Prerequisites

* Node.js
* npm

### Installation

```bash
git clone https://github.com/nikunj-10/hotel-booking.git

cd hotel-booking

npm install

npm start
```



## Available Scripts

### Start Development Server

```bash
npm start
```

Runs the application in development mode.

### Run Tests

```bash
npm test
```

Launches the test runner.

### Production Build

```bash
npm run build
```

Creates an optimized production build.



## Future Enhancements

* Payment Gateway Integration
* Hotel Owner Dashboard
* Room Reviews and Ratings
* Booking Notifications
* Advanced Search and Recommendations



## Author

Nikunj Agarwal

LinkedIn:
https://www.linkedin.com/in/nikunj-agarwal-326b562a4

GitHub:
https://github.com/nikunj-10

```
```
