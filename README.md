# IAE (Integrated Application Environment)

## Overview
IAE is a web-based food ordering and restaurant booking application. It provides a platform for users to browse restaurants, order food, make reservations, and more.

## Features
- User authentication and registration
- Restaurant browsing and search
- Food ordering system
- Cart management
- Restaurant booking
- Partner/Restaurant dashboard
- Admin panel for user management
- Contact and review system

## Technology Stack
- **Backend**: Node.js, Express.js
- **Frontend**: EJS, HTML, CSS, JavaScript
- **Database**: MongoDB
- **Authentication**: bcrypt

## Dependencies
- bcrypt
- body-parser
- cookie-parser
- ejs
- express
- express-ejs-layouts
- express-session
- mongoose

## Installation

1. Clone the repository
   ```
   git clone [repository URL]
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Set up MongoDB
   - Make sure MongoDB is installed and running on your system
   - Default connection: mongodb://localhost:27017/project

4. Start the application
   ```
   node app.js
   ```

5. Access the application
   ```
   Open your browser and navigate to http://localhost:8000
   ```

## Project Structure
- **controllers/**: Contains application controllers
- **models/**: Database models
- **public/**: Static assets (CSS, images, etc.)
- **routes/**: Application routes
- **scripts/**: JavaScript files
- **views/**: EJS templates and views

## License
ISC 