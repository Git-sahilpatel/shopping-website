# 🛍️ Shopping Website

This is a basic Shopping Website project built using **PHP**, **HTML**, **CSS**, and **MySQL**. It includes features like product listing, user login/register, shopping cart, and order management.

## 🔧 Features

- User registration and login
- Product browsing by category
- Add to cart functionality
- Checkout and order confirmation
- Admin panel (optional)
- Responsive design (basic)

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Tools:** XAMPP / WAMP / MAMP

## 💡 How to Run

1. **Extract the files**
   - Place the extracted project folder in your web server root (`htdocs` for XAMPP).

2. **Import the database**
   - Open phpMyAdmin
   - Create a new database (e.g., `shopping`)
   - Import the `.sql` file (if provided) from the project directory

3. **Configure database**
   - Open `config.php` or similar file
   - Set your DB username/password:
     ```php
     $conn = new mysqli("localhost", "root", "", "shopping");
     ```

4. **Start the server**
   - Open XAMPP/WAMP/MAMP and start Apache and MySQL
   - Go to `http://localhost/shopping` in your browser

## 📁 Project Structure

# shopping-website
