🛍️ GEN_Z CLOTHING — Online Clothing Store

A full-stack web application for an online clothing store built with **PHP**, **JavaScript**, **HTML**, and **CSS**. 
The project features a customer-facing storefront, an admin panel, product management, user authentication, and database connectivity.

📌 About the Project
**GEN_Z CLOTHING** is a dynamic e-commerce web application that allows customers to browse and purchase clothing items such as Jeans, T-Shirts, and Blouses. 
The platform includes a full admin dashboard for managing products, customers, and orders, as well as a customer registration and login system.

✨ Features
🛒 Customer Side
- Browse clothing categories (Jeans, T-Shirts, Blouses, etc.)
- View product listings and details
- User registration and login
- Contact page for inquiries
- View available offers and deals

# Admin Side
- Admin login and dashboard
- Add, update, and delete products
- Manage customer records
- View and manage orders

# General
- Reusable PHP components (Header, Footer, Right sidebar)
- Form validation using JavaScript
- MySQL database integration
- Responsive layout with custom CSS

# Tech Stack

 Technology & Purpose 
 PHP - Server-side scripting & backend logic 
 MySQL - Database (via `/db` and `/Connections`) 
 JavaScript - Client-side form validation 
 HTML / CSS - Structure and styling 
 Spry Assets - Adobe Dreamweaver UI components 
 
📁 Project Structure
Online-Clothing-Store 
├── Admin/                  # Admin panel pages
├── Connections/            # Database connection files
├── Customer/               # Customer-related pages
├── Products/               # Product listing pages
├── SpryAssets/             # Spry UI framework assets
├── _mmServerScripts/       # Dreamweaver server scripts
├── _notes/                 # Dreamweaver project notes
├── db/                     # Database files / SQL scripts
├── img/                    # Product and UI images
│
├── index.php               # Homepage (Welcome / Landing page)
├── index.html              # Static HTML entry point
├── login.php               # User login page
├── Register.php            # User registration page
├── Products.php            # Products listing page
├── Category.php            # Category browsing page
├── Offers.php              # Offers and deals page
├── Contact.php             # Contact us page
├── Insert.php              # Insert/add product logic
├── Header.php              # Reusable site header
├── Footer.php              # Reusable site footer
├── Right.php               # Right sidebar component
├── Sample.php              # Sample/test page
├── style.css               # Main stylesheet
├── gen_validation.js       # JavaScript form validation
└── .gitattributes          # Git configuration


# Getting Started
# Prerequisites
Make sure you have the following installed:
- [XAMPP](https://www.apachefriends.org/) or [WAMP](https://www.wampserver.com/) (Apache + PHP + MySQL)
- A web browser (Chrome, Firefox, etc.)
- Git

### Installation
1. **Clone the repository:**
git clone https://github.com/GKNithish/Online-Clothing-Store.git

2. **Move the project to your server's root directory:**
# For XAMPP
cp -r Online-Clothing-Store /xampp/htdocs/

# For WAMP
cp -r Online-Clothing-Store /wamp/www/

3. **Set up the database:**

   - Open **phpMyAdmin** at `http://localhost/phpmyadmin`
   - Create a new database (e.g., `clothing_store`)
   - Import the SQL file from the `/db` folder

4. **Configure the database connection:**

   - Open the files inside `/Connections/`
   - Update the database host, username, password, and database name to match your local setup

5. **Start your local server** (Apache + MySQL) via XAMPP/WAMP Control Panel.

6. **Visit the app in your browser:**
http://localhost/Online-Clothing-Store/index.php
```
# Contributing
Contributions are welcome! To contribute:
1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

# Author

Nithish G
GitHub: [@GKNithish](https://github.com/GKNithish)

This project is open source and available under the [MIT License](LICENSE).
