# Inventory Management Application

This is a simple web-based inventory management application built using Django on the backend and Bootstrap for the frontend.

## Features

- **User Authentication:** Allows users to sign up, log in, and log out. Differentiates between regular users and admin users.
- **Product Management:** Admin users can add, edit, and delete products.
- **Category Management:** Admin users can manage categories for products.
- **Inventory Tracking:** Keeps track of the quantity of each product in stock.
- **Order Management:** Allows users to place orders and admin users to view and process them.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/rebel47/Inventory-Management
```

2. Create a virtual environment and install dependencies:

```bash
cd inventory-management
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
```

3. Set up the database:

```bash
python manage.py migrate
```

4. Create an admin user:

```bash
python manage.py createsuperuser
```

5. Start the development server:

```bash
python manage.py runserver
```

6. Open your web browser and navigate to `http://localhost:8000` to access the application.

## Configuration

- The application uses the default SQLite database. If you need to use a different database, update the settings in `settings.py`.

## Usage

- Log in with your admin credentials to access the admin dashboard where you can manage products, categories, and view orders.
- Regular users can view products, add them to the cart, and place orders.


## Dependencies

- Django
- Bootstrap

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Django and Bootstrap communities for providing excellent documentation and resources.

## Contributing

If you'd like to contribute, please fork the repository and create a pull request. You can also open an issue if you find any bugs or have suggestions for improvements.

## Contact

For any questions or feedback, feel free to reach out at your@email.com.

---
