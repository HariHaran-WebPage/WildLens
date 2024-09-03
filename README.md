# WildLens Tour Website

**WildLens** is a comprehensive tourism booking website designed to provide users with a seamless experience for booking tours, reserving seats, and making payments. The project leverages modern web technologies to offer a fast, responsive, and secure platform for travelers.

## Project Overview

- **Frontend**: React with Vite
- **Backend**: Node.js with Express
- **Database**: MongoDB Atlas
- **Payment Integration**: Razorpay
- **Deployment**: [WildLens Tour Website]((https://wildlenstour.netlify.app/home))

## Features

- **Tour Booking**: Users can browse and book various tours offered by WildLens.
- **Seat Reservation**: Users can reserve seats for tours, ensuring they have a spot on their desired date.
- **Guided Assistance**: Options to select guided tours, providing a knowledgeable guide for the journey.
- **Secure Payments**: Integrated with Razorpay for a secure and seamless payment experience.
- **User Authentication**: Secure user authentication system to manage bookings and user information.
- **Responsive Design**: The website is optimized for all devices, providing a consistent experience across desktops, tablets, and mobile devices.

## Tech Stack

- **Frontend**: 
  - **React**: For building the user interface.
  - **Vite**: For fast build times and optimized performance.
- **Backend**:
  - **Node.js**: For handling server-side logic.
  - **Express**: For managing routes and server-side functionality.
- **Database**: 
  - **MongoDB Atlas**: Cloud-based database for storing user and tour data.
- **Payment Gateway**: 
  - **Razorpay**: For processing secure payments.

## Setup and Installation

### Prerequisites

- Node.js installed
- MongoDB Atlas account
- Razorpay account

### Steps to Run the Project Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/wildlens-tour-website.git
   cd wildlens-tour-website


Install backend dependencies:
cd backend
npm install
----------- ---------------------------------

Configure environment variables:

Create a .env file in the backend directory and add your MongoDB connection string and Razorpay keys:

MONGO_URI=your_mongodb_connection_string
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret



