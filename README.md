# Hospital Management System

## Project Overview

This Hospital Management System was developed as part of an internship at Edunet under AICTE and EY. The project aimed to create a comprehensive management system for hospitals to manage patient records, appointments, and other administrative tasks. I was responsible for the frontend development, while the backend was handled by other team members. The project was built using HTML, CSS, JavaScript, and Django.

This project was a significant milestone in my internship, leading to my name being listed on the merit list, and I received a certificate for this achievement.

## Features

- **Patient Management:** Allows hospital staff to add, view, and update patient records.
- **Appointment Scheduling:** Enables the scheduling and management of patient appointments.
- **Dashboard:** A user-friendly interface that provides an overview of hospital operations.
- **Responsive Design:** The interface is designed to be responsive, ensuring accessibility across devices.

## Technologies Used

- **HTML:** For the structure and layout of the web pages.
- **CSS:** For styling and ensuring a consistent look and feel across the application.
- **JavaScript:** For interactive elements and enhancing user experience.
- **Django:** A Python-based web framework used for handling backend operations and data management.

## Project Structure

```plaintext
Hospital-Management-System/
│
├── frontend/
│   ├── index.html          # The homepage/dashboard
│   ├── patients.html       # Page for managing patient records
│   ├── appointments.html   # Page for managing appointments
│   ├── css/
│   │   └── styles.css      # Stylesheet for the frontend
│   ├── js/
│   │   └── script.js       # JavaScript for interactivity
│   └── images/
│       └── *               # Images used in the frontend
│
└── backend/
    ├── manage.py           # Django management script
    ├── app/
    │   ├── models.py       # Models for the database
    │   ├── views.py        # Views to handle requests
    │   ├── templates/      # Django templates
    │   └── static/         # Static files like CSS and JS
    └── db.sqlite3          # SQLite database used for development
```

## How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/DR-Vora/Hospital-Management-System.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd Hospital-Management-System
   ```

3. **Set Up the Django Environment:**
   - Install the required dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Apply migrations to set up the database:
     ```bash
     python manage.py migrate
     ```

4. **Run the Django Development Server:**
   ```bash
   python manage.py runserver
   ```

5. **Explore the Application:**
   - Open your browser and go to `http://localhost:8000` to interact with the application.

## Acknowledgements

This project was developed during my internship at Edunet under AICTE and EY. I am grateful for the opportunity and the guidance provided by my mentors.

## Achievements

- My contributions to this project led to my inclusion on the merit list for the internship, and I received a certificate for this accomplishment.

## License

This project is licensed under the MIT License.
