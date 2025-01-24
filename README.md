# Natours 🌿

**Natours** is a backend API for a fictional nature tour booking platform. Built with Node.js, Express, MongoDB, and Mongoose, it provides a robust and scalable solution for managing tours, users, bookings, and reviews.

---

## Features 🚀

- **User Authentication**: JWT-based signup/login with password encryption.
- **Tours Management**: 
  - CRUD operations for tours.
  - Filter, sort, paginate, and search tours.
  - Geospatial queries for tours within a radius.
- **Reviews & Ratings**: Users can leave reviews and ratings for tours.
- **Booking System**: Secure tour bookings with Stripe integration (mock implementation).
- **Security Best Practices**: 
  - Rate limiting, CORS, and HTTP headers.
  - Data sanitization against NoSQL injection and XSS.
- **Error Handling**: Custom error handling middleware for development and production.
- **Email Notifications**: Send welcome emails, password reset emails, and booking confirmations.
- **Admin Features**: Restricted routes for admins to manage data.

---

## Installation 💻

### Prerequisites
- Node.js (v14+)
- MongoDB (local or cloud instance)
- npm or yarn

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/natours.git
   cd natours
