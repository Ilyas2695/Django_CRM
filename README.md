# Django CRM

This is a simple yet powerful Django CRM system for managing company-customer interactions. It provides a clear and intuitive interface for tracking customer details, interactions, and communications.

## Features

- Customer management: Create, update, and delete customer records.
- Interaction tracking: Log calls, emails, and meetings with customers.
- User authentication: Secure login system and user management.
- Responsive design: Accessible via various devices including mobile and tablet.

## Installation

Before you begin, ensure you have Python and Django installed on your system. If not, you can download Python from [python.org](https://www.python.org/) and follow the instructions to install Django with:

```bash
pip install django

1.Clone the repository

git clone https://yourrepositorylink.com/djangocrm.git
cd djangocrm

2.Set up a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3.Install dependencies

pip install -r requirements.txt

4.Initialize the database

python manage.py makemigrations
python manage.py migrate

5.Create an admin user

python manage.py createsuperuser
follow the prompts to create your admin user

6.Run the server

python manage.py runserver

Open your web browser and go to http://127.0.0.1:8000/ to view the application.

Usage

Log in using the superuser credentials you created, and begin by adding customer records. Navigate the interface to access different CRM features.

Customization

You can customize the CRM by modifying the templates found in the templates directory and extending the functionality in the views.py files of each app.

Contributing

I welcome contributions to this project. Please fork the repository and submit a pull request with your features or fixes.
