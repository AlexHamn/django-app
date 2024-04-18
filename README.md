# Django Basic App

This is a simple Django application that demonstrates basic functionality and serves as a starting point for learning Django. The app connects to a database and displays a list of tasks along with their completion status.

## Features

- Connects to a database to store and retrieve tasks
- Displays a list of tasks with their completion status (completed or not)
- Provides a foundation for learning and exploring Django's core concepts

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/AlexHamn/django-app.git
   ```

2. Navigate to the project directory:

   ```
   cd django-app
   ```

3. Set up the database:

   ```
   python manage.py migrate
   ```

4. Create a superuser (optional):

   ```
   python manage.py createsuperuser
   ```

## Configuration

The app follows standard Django configuration practices. You can customize the settings in the `settings.py` file located in the project directory.

## Usage

To run the app, use the following command:

```
python manage.py runserver
```

This will start the development server, and you can access the app by navigating to `http://localhost:8000` in your web browser.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## Resources

For more information on Django and its features, refer to the official Django documentation:

- Django Documentation: [https://docs.djangoproject.com/](https://docs.djangoproject.com/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

This app was created as a learning resource and is based on the Django web framework. Special thanks to the Django community for their excellent documentation and resources.