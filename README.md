# Wanna Talk About It - Blog Website with Flask

This is a blog website developed using Flask, a Python web framework. The project allows users to create, read, update, and delete blog posts, as well as register, log in, and comment on posts. The frontend of the website was provided by my course instructor Angela Yu, while the backend functionality was implemented by me.

## Features

- User Registration: Users can sign up for an account by providing their name, email, and password.

- User Authentication: Registered users can log in to their accounts securely.

- Create Blog Posts: Authenticated users can create new blog posts by providing a title, subtitle, image URL, and content.

- Comment on Posts: Users can leave comments on blog posts to engage with the content.

- Edit and Delete Posts: Authors can edit and delete their own posts.

- Admin Functionality: An admin user has additional privileges, such as editing and deleting any post.

## Technologies Used

- **Flask**: A lightweight Python web framework used for building the backend of the application.

- **SQLAlchemy**: A SQL toolkit and Object-Relational Mapping (ORM) library for Python, used for database interactions.

- **Flask-Login**: A Flask extension for handling user sessions and authentication.

- **Flask-WTF**: An integration of the WTForms library for handling web forms in Flask.

- **Flask-CKEditor**: An extension for integrating the CKEditor rich text editor into Flask forms.

- **Flask-Gravatar**: An extension for generating Gravatar URLs based on user email addresses.

- **Bootstrap**: A popular front-end framework for responsive web design.

## Setup and Installation

1. Clone this repository to your local machine.

```bash
git clone https://github.com/ozesince02/Blog-Website-Flask.git
```

2. Create a virtual environment and activate it.

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages using pip.

```bash
pip install -r requirements.txt
```

4. Configure the database URI in the `app.config['SQLALCHEMY_DATABASE_URI']` field in `main.py`. You can use SQLite for development, but consider using a more robust database for production.

5. Initialize the database.

```bash
python main.py
```

6. Start the development server.

```bash
flask run
```

The website should now be accessible at `http://localhost:5000`.

## Usage

- Visit the website and register for an account.
- Log in with your credentials.
- Create blog posts, edit them, or delete them.
- Leave comments on blog posts.

## Credits

- Frontend templates, CSS, and Bootstrap: Provided by Angela Yu as part of the course material.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to Angela Yu for providing the frontend resources and inspiration for this project.
