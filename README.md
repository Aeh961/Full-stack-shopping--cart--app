🛒 Shopping Cart Application

A full-stack shopping cart application built with Node.js and MongoDB that allows customers to browse products, manage their cart, and place orders, while providing an admin panel for managing inventory and viewing customer orders.

🔹 Overview

This project simulates a basic e-commerce platform with both customer and admin functionality.

Customers can browse available products, add items to their cart, and update their orders in real time.
Admins can manage inventory by adding, editing, or deleting items, as well as viewing customer orders.

🔹 Features
👤 Customer Features
View available products
Add items to cart
Remove items from cart
Update item quantities
View and manage current order
🛠 Admin Features
Add new products
Edit existing products
Delete products
View all customer orders
🔹 Tech Stack
Backend: Node.js
Database: MongoDB (via Mongoose)
Frontend: HTML, CSS, JavaScript
Tools: Express (if used), Git
🔹 Project Structure
Shopping-Cart/
│── public/
│   ├── javascript/
│   │   └── clickactions.js   # Contains admin credentials & client-side logic
│
│── models/                   # Mongoose schemas (Items, Orders, Customers)
│── routes/                   # API routes (if applicable)
│── views/                    # Frontend pages
│
│── initItemsDB.js            # Seed items database
│── initOrdersDB.js           # Seed orders database
│── customerInitDB.js         # Seed customer database
│
│── app.js / server.js        # Main server entry point
│── README.md
🔹 How It Works
The application initializes the database with sample data
Users land on the homepage and browse available items
Customers:
add items to their cart
update quantities or remove items
Admin:
logs in using credentials from clickactions.js
manages product inventory
views customer orders
🔹 Setup & Installation
1. Install dependencies
npm install
2. Initialize the database

Run the following commands:

node initItemsDB.js
node initOrdersDB.js
node customerInitDB.js

(Adjust file names if needed based on your actual repo)

3. Start the server
node app.js
4. Open the application

Go to:

http://localhost:3000
🔹 Admin Access

Admin credentials are stored in:

public/javascript/clickactions.js

Use these credentials to:

manage products
view customer orders
🔹 Key Concepts Demonstrated
Full-stack application structure
REST-style routing and backend logic
Database modeling with Mongoose
CRUD operations (Create, Read, Update, Delete)
Separation between admin and customer functionality
🔹 Future Improvements
Move admin credentials to a secure authentication system
Add user login and authentication
Integrate payment processing
Improve UI/UX design
Deploy application to cloud (AWS, Vercel, etc.)
🔹 Author

Abdallah El Hamawi
MS Software Development, Boston Universitye
