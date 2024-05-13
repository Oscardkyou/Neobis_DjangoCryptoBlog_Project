# Crypto/Blog News Portal

## Overview

Django Crypto/Blog News Portal is a web-based platform where users can read and post news articles. This project was built using the Django framework to demonstrate the ability to create a full-featured web application. It incorporates fundamental web development technologies and showcases CRUD operations in a clean and user-friendly interface.

## Technologies Used

- Python 3
- Django Framework
- HTML
- Django Forms
- Django Template

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/crypto/blog.git
2. **Navigate to the project directory:**

3. **Install required packages:**
pip install -r requirements.txt
4. **Run migrations:**
python manage.py migrate
5. **Start the development server:**
python manage.py runserver

## Usage
After starting the server, visit `http://127.0.0.1:8000/admin` in your browser to access the Django Admin interface. Here you can manage your news portal:

- **Add a new post:**
  - Navigate to the Django Admin at `/admin`.
  - Go to Posts or Articles section (depending on your model naming).
  - Click on the 'Add' button to submit a new news article.

- **View all posts:**
  - All posts can be viewed in the Django Admin under the Posts or Articles section. This allows administrative users to manage and view all submissions.

Make sure you have superuser access to interact with the admin panel. If you have not created a superuser yet, you can create one by running:

python manage.py createsuperuser


## Contributing
Contributions are welcome! If you have suggestions for improvements or bug fixes, feel free to fork this repository and submit a pull request.

## Authors
[Dk](https://github.com/oscardkyou)


## Screenshots
![Home Page](img\123.png)

## Key Considerations
- Ensure simplicity and clarity in code and UI.
- Use comments to explain complex sections of code.
- Document your code adequately to help future contributors understand and work with it.
