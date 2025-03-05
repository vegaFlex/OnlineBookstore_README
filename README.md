# Online Bookstore - Documentation

This is the public documentation for the **Online Bookstore** project.

## 📌 Access to the Original Code
This project is private. If you wish to access the original repository, please send a request.

🔒 **Link to the original repository:** [Online Bookstore (private repo)](https://github.com/vegaFlex/Online_Bookstore) *(requires approval)*

📩 If you would like access, please send me a direct message on GitHub or contact me at [veslin.lilov@gmail.com](mailto:veslin.lilov@gmail.com).

---

# Online Bookstore

An online bookstore built with Django, allowing users to browse books, add them to the cart and favorites, manage orders, and process payments via Stripe.

---

## Table of Contents
1. [Features](#features)  
2. [Installation & Setup](#installation--setup)  
3. [Core Modules](#core-modules)  
4. [JavaScript & Interactive Features](#javascript--interactive-features)  
5. [Admin Panel](#admin-panel)  
6. [Technologies](#technologies)  
7. [Contact & Support](#contact--support)  

---

## Features
- User registration and authentication
- Book browsing and search functionality
- Add books to cart and favorites
- Order management and Stripe payment processing
- Admin panel for managing books, categories, orders, and reviews

---

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/vegaFlex/Online_Bookstore.git
cd Online_Bookstore
```

### 2. Create a Virtual Environment
```sh
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

### 4. Database Setup
```sh
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a Superuser
```sh
python manage.py createsuperuser
```

### 6. Run the Server
```sh
python manage.py runserver
```

Project is accessible at: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)  
After deployment: [https://bookzone-bg-ckd0b9b3abdvfncx.italynorth-01.azurewebsites.net/](https://bookzone-bg-ckd0b9b3abdvfncx.italynorth-01.azurewebsites.net/)  

---

## Core Modules

### 1. Pages & Navigation
- **Home Page** – Displays featured and new books
- **Book Details** – Provides book descriptions, pricing, and an option to add to cart
- **Favorites** – Allows users to save books for later
- **Cart** – Enables viewing, updating, and checking out

### 2. Order Management
- **Add books to cart via AJAX**
- **Checkout process** – Enter address, select payment method (credit card or cash on delivery)
- **Order storage in the database**
- **Stripe integration for payment processing**

### 3. Admin Panel
- Manage books, categories, and publishers
- View and process orders
- Approve or reject user reviews
- Manage homepage sliders and static page content

---

## JavaScript & Interactive Features
- **AJAX-based cart and favorites functionality**
- **Toast notifications for success messages**
- **Interactive book slider**
- **Dynamic dropdown menus for categories and profile**

---

## Admin Panel

🔗 **Access:** [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)  
After deployment: [https://bookzone-bg-ckd0b9b3abdvfncx.italynorth-01.azurewebsites.net/admin/](https://bookzone-bg-ckd0b9b3abdvfncx.italynorth-01.azurewebsites.net/admin/)  

### Admin Features
- **Books:** Add, edit, delete books
- **Categories & Publishers:** Manage book classification
- **Orders:** View, update, and change order status
- **Reviews:** Approve or reject customer reviews
- **Sliders:** Manage homepage banners
- **Static Pages:** Control footer and about page content

---

## Technologies
- **Backend:** Django, PostgreSQL
- **Frontend:** TailwindCSS, JavaScript (AJAX)
- **Payments:** Stripe API
- **Deployment:** Azure

---

## Contact & Support
For questions or issues, contact **vegaFlex@github.com**.

