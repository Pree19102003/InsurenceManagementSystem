# Insurance Management System

A web-based Insurance Management System developed using Django. This application allows customers to view and apply for insurance policies while enabling administrators to manage policies, customers, and policy applications efficiently.

## Features

### Admin Module

* Admin Login
* Manage Customers
* Manage Insurance Categories
* Add, Update, and Delete Policies
* View Policy Applications
* Approve or Reject Applications
* View Customer Queries

### Customer Module

* Customer Registration and Login
* View Available Insurance Policies
* Apply for Insurance Policies
* Track Application Status
* View Policy History
* Submit Queries to Admin

## Technology Stack

| Technology | Purpose             |
| ---------- | ------------------- |
| Python     | Backend Programming |
| Django     | Web Framework       |
| SQLite     | Database            |
| HTML       | Frontend Structure  |
| CSS        | Styling             |
| Bootstrap  | Responsive Design   |

## Project Structure

```text
insurance_management/
│
├── insurance/
├── customer/
├── templates/
├── static/
├── db.sqlite3
├── manage.py
└── requirements.txt
```

## Installation

### Clone the Repository

```bash
git clone <repository-url>
cd insurance_management
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Database Migration

```bash
python manage.py makemigrations
python manage.py migrate
```

## Create Superuser

```bash
python manage.py createsuperuser
```

Follow the prompts to create the administrator account.

## Run the Project

```bash
python manage.py runserver
```

Open your browser and navigate to:

```text
http://127.0.0.1:8000/
```

## Admin Panel

```text
http://127.0.0.1:8000/admin/
```

## Customer Module

Customer Registration:

```text
http://127.0.0.1:8000/customer/customersignup
```

Customer Login:

```text
http://127.0.0.1:8000/customer/customerlogin
```

## Requirements

```text
Django==3.0.5
django-widget-tweaks==1.4.8
asgiref==3.2.7
pytz==2020.1
sqlparse==0.3.1
```

## Future Enhancements

* Online Premium Payment Gateway
* Email Notifications
* Policy Renewal Reminders
* PDF Policy Reports
* Mobile Responsive Dashboard
* Data Analytics and Reporting

## Author

Developed as a Django-based Insurance Management System project for learning and academic purposes.

## License

This project is intended for educational and research purposes.
