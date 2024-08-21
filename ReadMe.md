
# PingMe Social Media Platform - Backend

🚀 Welcome to the backend of PingMe, a social media platform designed for seamless social interactions! This Node.js server handles authentication, user management, and post creation, with secure file storage and API routes.

## 🛠️ Features

- **User Authentication:** Sign up and log in securely.
- **Posts Management:** Create, view, and interact with posts.
- **File Uploads:** Upload images for profiles and posts.
- **Middleware Protection:** Secure routes with JWT authentication.
- **MongoDB Integration:** Efficient data handling using Mongoose.
- **Logging and Security:** Enhanced with Morgan and Helmet.

## 🚀 Getting Started

### Prerequisites

- Node.js
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/pingme-backend.git
   ```

2. Install dependencies:

   ```bash
   cd pingme-backend
   npm install
   ```

3. Create a `.env` file in the root directory with the following:

   ```
   MONGO_URL=your_mongodb_connection_string
   PORT=6001
   ```

4. Start the server:

   ```bash
   npm start
   ```

   The server will be running on `http://localhost:6001`.

## 📁 Folder Structure

- **/controllers**: Contains business logic for authentication and posts.
- **/middleware**: JWT verification middleware.
- **/models**: Mongoose models for User and Post.
- **/routes**: API routes for authentication, users, and posts.
- **/public/assets**: Static files for image storage.

## 📜 License

This project is licensed under the MIT License.
