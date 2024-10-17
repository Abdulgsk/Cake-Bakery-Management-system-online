# Cake Bakery System Online

## Project Overview
The **Cake Bakery System Online** is a web-based application designed for bakery businesses to allow customers to browse, select, and order cakes online. The system facilitates smooth interactions between the bakery and its customers by providing an efficient order management and payment processing platform.

## Features
- **Browse Cakes**: Customers can browse a variety of cakes categorized by flavor, occasion, and price.
- **Custom Cake Orders**: Option for customers to order personalized cakes by specifying designs, sizes, and custom messages.
- **User Authentication**: Users can register and log in to manage their profiles and order history.
- **Order Management**: Customers can view, edit, and track their cake orders.
- **Payment Integration**: Payment options for customers via credit card, PayPal, or cash on delivery.
- **Admin Dashboard**: The bakery admin can manage cake listings, view orders, and update order statuses.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Server**: Apache (via XAMPP/WAMP or a live web server)

## Project Structure
/cake-bakery-system/ │ ├── /assets/ # CSS, JavaScript, and images │ ├── /css/ # Styling for the frontend │ ├── /js/ # JavaScript for interactive elements │ └── /images/ # Cake images and other assets │ ├── /includes/ # PHP scripts for database connection and common functions ├── /pages/ # HTML and PHP pages for the system │ ├── home.php # Homepage with cake listings │ ├── product.php # Cake product detail page │ ├── cart.php # Shopping cart page │ └── checkout.php # Checkout and payment processing │ ├── /admin/ # Admin dashboard for managing the system │ ├── dashboard.php # Admin homepage │ ├── manage-cakes.php # Add/Edit/Delete cake listings │ └── orders.php # View and manage orders │ └── index.php # Main entry point for the application
## Database Structure
The system uses a MySQL database to store user and order information. Key tables include:

- **users**: Stores user information (name, email, password, etc.).
- **cakes**: Stores cake listings (name, category, price, description, image, etc.).
- **orders**: Stores order details (user, cake, quantity, total, status, etc.).

### Prerequisites
- XAMPP or WAMP (for running PHP and MySQL locally)
- Basic knowledge of PHP, MySQL, and HTML/CSS
