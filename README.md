# Merry Berry Smoothie & Açaí Shop

Welcome to **Merry Berry Smoothie & Açaí Shop**, a refreshing and healthy online store where you can explore a variety of delicious smoothies and açaí bowls! 🍓🍌🥑

## Table of Contents
- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## About
Merry Berry is an e-commerce platform that allows users to browse, customize, and order smoothies and açaí bowls. The platform is designed for a seamless and engaging user experience.

## Features
✅ Browse a variety of smoothies and açaí bowls  
✅ Customize orders with toppings and ingredients  
✅ Secure user authentication  
✅ Online payment integration  
✅ Order history and tracking  

## Tech Stack
- **Frontend:** React, TailwindCSS
- **Backend:** Flask, PostgreSQL
- **Authentication:** OAuth, JWT
- **Deployment:** Docker, AWS

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Node.js & npm
- PostgreSQL
- Docker (optional for containerization)

### Backend Setup
```bash
# Clone the repository
git clone https://github.com/your-username/merry-berry.git
cd merry-berry/backend

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Set environment variables (modify .env file as needed)
cp .env.example .env

# Run the server
flask run
```

### Frontend Setup
```bash
cd ../frontend
npm install
npm run dev
```

## Usage
1. Start the backend server.
2. Run the frontend development server.
3. Access the application at `http://localhost:3000`.

## API Endpoints
### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login and obtain JWT token

### Smoothies & Açaí
- `GET /api/products` - Fetch all available products
- `GET /api/products/:id` - Get product details

### Orders
- `POST /api/orders` - Place a new order
- `GET /api/orders/:id` - Get order details

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See `LICENSE` for more details.

---
_Enjoy your smoothies and happy coding!_ 🍹✨
