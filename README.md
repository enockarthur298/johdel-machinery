# J-Machinery - Professional Power Tools E-Commerce

This is an E-Commerce platform specializing in professional power tools and accessories, built using React for the frontend and Flask for the backend. The application allows customers to browse our extensive catalog of power tools, add items to their cart, and complete purchases securely.

## Features
- User authentication and authorization (registration, login, logout)
- Comprehensive product catalog with advanced search and filter functionality
- Shopping cart with item management
- Order management (view order history, track order status)
- Secure payment processing
- Admin panel for managing products and orders
- Product specifications and comparison tools for power tools

## Product Categories
- Power Drills and Drivers
- Saws (Circular, Jig, Reciprocating)
- Sanders and Grinders
- Air Compressors and Nail Guns
- Tool Accessories and Safety Gear

## Technologies Used

1. **Frontend**
  - React.js
  - Redux (for state management)
  - React Router (for navigation)
  - Axios (for API requests)
  - Bootstrap/Material-UI (for UI components)

2. **Backend**
  - Flask (Python)
  - Flask-RESTful (for creating REST APIs)
  - Flask-JWT-Extended (for JWT-based authentication)

## Prerequisites
- Node.js and npm (for the frontend)
- Python 3.x (for the backend)
- Flask
- Virtualenv (optional but recommended)

## Installation
1. **Backend Setup (Flask)**

  - Clone the repository:

        git clone https://github.com/yourusername/j-machinery.git
        cd j-machinery/backend

  - Create a virtual environment:

        python3 -m venv venv
        source venv/bin/activate  # On Windows use `venv\Scripts\activate`

  - Run the backend server:

        flask run

2. **Frontend Setup (React)**
  - Navigate to the frontend directory:

        cd ../frontend

  - Install the required dependencies:

        npm install

  - Configure your API endpoint in src/config.js:

        export const API_BASE_URL = 'http://localhost:5000/api';

  - Start the React development server:

        npm start

  - Running the Application
    
        The backend server will run at http://localhost:5000.
        The React frontend will run at http://localhost:3000.
    
To access the application, open your browser and navigate to http://localhost:3000.
