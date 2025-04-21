# ***Online Store***

This is an online store project built with Python using the Django framework. The project includes basic functionality for managing products, categories, orders, and users.


# ***Key Features***
+ **Product Catalog** : View a list of products with filtering by categories.
+ **User Authentication** : Registration, login, and profile management.
+ **Shopping Cart and Checkout** : Add products to the cart and place orders.
+ **Admin Panel** : Manage products, categories, and orders via Django Admin
+ **Product Search**  : Search for products by name or description.

# ***Technologies***

+ **Backend**  : Django (version 4.2.7).
+ **Database** : PostgreSQL (via psycopg2), with SQLite supported for development.
+ **Frontend** : HTML, CSS, JavaScript (Bootstrap may be used for styling).
+ **Debugging** : Configured with django-debug-toolbar for easier development.
+ **Other Tools**
    + Pillow for image processing.
    + Colorama for colored console output.

# ***How to Run the Project***
**Prerequisites**
1. Install Python 3.8+.
2. Install PostgreSQL (if you want to use it instead of SQLite).
3. Install Git.

# ***Steps to Run***
1. **Clone the Repository**

    ```
    git clone https://github.com/Online-store.git
    cd Online-store
    ```

2. **Create a Virtual Environment**
    ```
    python -m venv venv
    source venv/bin/activate  # For Linux/MacOS
    venv\Scripts\activate     # For Windows
    ```

3. **Install Dependencies**
    ```
    pip install -r requirements.txt
    ```
4. **Apply Migrations**
    ```
    python manage.py migrate
    ```
6. **Create a Superuser (for Admin Access)**
    ```
    python manage.py createsuperuser
    ```
7. **Run the Server**
    ```
    python manage.py runserver
    ```

# ***Additional Information***
**Admin Panel**

You can manage products, categories, and orders via the Django Admin panel:

1. Go to: http://127.0.0.1:8000/admin .
2. Enter the superuser login and password.

**Docker (Optional)**

1. Ensure you have Docker and Docker Compose installed.
2. Build and run the containers:

    ```
    docker-compose up --build
    ```

