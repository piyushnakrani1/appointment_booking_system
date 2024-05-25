# Appointment Booking System - Project Setup

## Technologies Used

- Python 3.10
- Django
- Djongo (for MongoDB integration)
- Django REST Framework
- React
- MongoDB(Database)

**Clone the Repository**: Clone this repository to your local machine using the following command:

```
git clone https://github.com/piyushnakrani1/appointment_booking_system.git
```

## Setup Backend
1. **Setup Mongo DB in your Local System**: Reference Link :- https://www.mongodb.com/docs/v3.0/tutorial/

2. **Create Python virtual environment**:
    ```
    python3 -m venv env
    ```
    ```
    source env/bin/activate
    ```

6. **Install Dependencies**: Navigate to the project directory and install the required Python dependencies using pip:

    ```
    cd doctor_booking
    ```
    ```
    pip install -r requirements.txt
    ```
    
7. **Run Migrations**: Apply database migrations to create the necessary tables in the MongoDB database:

    ```
    python manage.py migrate
    ```
8. **Load Doctors Data**: Insert the Doctors Data in MongoDB Database using the following command:

    ```
    python manage.py insert_doctor_data
    ```
9. **Start the Development Server**: Run the Django development server using the following command:

    ```
    python manage.py runserver
    ```

10. **Access the API**: Once the server is running, you can access the API endpoints at `http://localhost:8000/api/`.

## Setup Frontend
**Open another terminal for setting up frontend**

1. **Install Dependencies**: Run the following command to install all the necessary dependencies:

    ```
    cd doctor-booking-client/
    ```
    ```
    npm install
    ```
2. **Run Project**: Run the following command to run the frontend:

    ```
    npm start
    ```
