# Food Delivery Service Website - Freaky Food

Freaky Food is a **food delivery service website** that enables users to explore area restaurants, view menus, place orders, write reviews, and save favorite spots. It caters to various user roles, including customers, vendors, and drivers, each with distinct interfaces and functionalities.


## Core Features

- **Restaurant Listings**: Browse area restaurants effortlessly.
- **Menu Viewing**: View detailed menus for each restaurant.
- **Order Creation**: Create and place orders quickly.
- **Reviews**: Write reviews and read feedback from other users.
- **Favorites**: Save and manage favorite restaurants.
- **Authentication**: Secure login and account creation for all users.
- **User Role Interfaces**: 
  - **Customers**: Place orders, write reviews, and save favorites.
  - **Vendors**: Manage restaurant listings, menus, and track orders.
  - **Drivers**: View delivery routes and manage pending orders.

## Installation Instructions

### Prerequisites
- Python 3.10 or higher
- pip (Python package manager)
- Git

### Steps to Install

1. **Clone the Repository**
 ```bash
  git clone https://github.com/your-username/freaky-food.git
  cd freaky-food
 ```
2. **Create and Activate a Virtual Environment**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```
3. **Install Dependencies**
  ```bash
  pip install -r requirements.txt
  ```
4.  **Run the Project**
  - With Mock Data
    ```bash
    python project/app.py --reset-db
    ```
  - Without Mock Data
    ```bash
    python project/app.py
    ```
