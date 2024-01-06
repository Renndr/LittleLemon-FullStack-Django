# LittleLemon Restaurant Django Project

## Description

#### This is a proyect for Meta Back end developer 

LittleLemon is a Django project for a restaurant that provides an API to view menu items and a booking form. The project uses SQLite as the database for simplicity.

## Features

- **Menu API:** Access the menu items through a simple API.
- **Booking Form:** Allows users to submit booking requests.
- **SQLite Database:** Utilizes SQLite for storing menu information and booking data.
- **Django Rest Framework:** Employs Django Rest Framework for building the API.

## Prerequisites

- Python (version 3.x)
- Django
- Django Rest Framework

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/littlelemon.git
   cd littlelemon
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Migrations:**
   ```bash
   python manage.py migrate
   ```

4. **Create Superuser (Optional):**
   ```bash
   python manage.py createsuperuser
   ```

5. **Run the Development Server:**
   ```bash
   python manage.py runserver
   ```

   The project will be available at `http://127.0.0.1:8000/`.

6. **Access Admin Panel (Optional):**
   - Visit `http://127.0.0.1:8000/admin/` to access the Django admin panel.

## API Endpoints

- **Menu API Endpoint:** `/api/menu/`
  - View the menu items.

## Usage

- **Menu API:**
  - Access the menu items by making a GET request to `/api/menu/`.

- **Booking Form:**
  - Users can submit booking requests through a form.

## License

This project is licensed under the [MIT License](LICENSE).
