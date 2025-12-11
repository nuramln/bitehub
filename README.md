# BiteHub — Restaurant Management System

## Project Description
BiteHub is a web-based restaurant management system designed for admins and staff to manage daily operations. The system provides functionalities for user registration, login, dashboard analytics, menu management, order tracking, and customer feedback. It is built to streamline restaurant operations and provide a clear overview of performance metrics.

---

## Features Included
- **User Authentication**
  - Admin and staff can register and log in securely.
  - Password validation ensures confirmation and uniqueness.
- **Dashboard**
  - Displays daily revenue, total orders, average expense, and average revenue.
  - Visual charts for Sales by Order Type and Orders Per Day.
  - Carousel banners for announcements.
- **Menu Management**
  - View and manage menu items with stock status indicators (High, Medium, Low, Out of Stock).
  - Responsive card layout for food items.
- **Order Management**
  - Table view of customer orders with ID, name, item, total, and status.
  - Filter and search orders by status (New, Preparing, Delivered, Cancelled).
- **Customer Feedback**
  - View customer reviews with category tags (Food, Delivery, Service).
  - Filter feedback by category.
  - Star ratings displayed for each review.
- **Responsive Design**
  - Sidebar and main content adjust for desktop and mobile screens.

---

## Instructions to Test Login
1. Open `index.html` in a web browser.
2. If you are a new user:
   - Click **Register** to create a new account.
   - Fill in Full Name, Username, Password, and Confirm Password.
   - Click **Register**. You will be redirected to the login page.
3. To log in:
   - Enter your **Username** and **Password**.
   - Click **Login**.
   - On successful login, you will be redirected to the **dashboard.html** page.
4. Error messages will appear for:
   - Empty fields
   - Username not found
   - Incorrect password

---

## Frameworks/Libraries Used
- **Bootstrap 5.3** — for responsive UI components and styling.
- **Chart.js** — for displaying dynamic charts in the dashboard.
- **JavaScript** — for form validation, localStorage management, and interactive features.
