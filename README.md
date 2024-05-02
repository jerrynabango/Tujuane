# Tujuane Chat App

Tujuane is a simple chat application created using Django framework. It allows users to communicate with each other in real-time through text messages.

## How to Run Tujuane Chat App

To run Tujuane on your local machine, follow these steps:

### 1. Clone the Repository

```
git clone https://github.com/jerrynabango/Tujuane.git
```

### 2. Navigate to the Project Directory

```
cd Tujuane
```

### 3. Install Dependencies

Ensure you have Python and pip installed on your system. Then, install the required dependencies by running:

```
pip install -r requirements.txt
```

### 4. Perform Database Migrations

Run the following command to apply database migrations:

```
python manage.py migrate
```

### 5. Create Superuser (Optional)

If you want to access the Django admin interface, create a superuser account by running:

```
python manage.py createsuperuser
```

Follow the prompts to create a superuser account.

### 6. Run the Development Server

Start the Django development server by running:

```
python manage.py runserver
```

By default, the server will run on `http://127.0.0.1:8000/`.

### 7. Access the Tujuane Chat App

Open your web browser and navigate to `http://127.0.0.1:8000/` to access the Tujuane chat app. You can sign up for a new account or log in with existing credentials to start chatting with other users.

### 8. Admin Interface

If you created a superuser account, you can access the Django admin interface at `http://127.0.0.1:8000/admin/`. Log in with your superuser credentials to manage users and view chat logs.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request on [GitHub](https://github.com/jerrynabango/Tujuane.git). 

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.