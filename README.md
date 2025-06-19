🏥 Hospital Management System
A web-based Hospital Management System built with Flask, SQLite3, HTML5, Tailwind CSS, and JavaScript to streamline healthcare services for doctors and patients. This system enables role-based login, appointment booking, patient management, prescriptions, medical records, and more.

🚀 Features
🔒 Authentication
Secure login and registration for doctors and patients

👨‍⚕️ Doctor Dashboard
View and manage appointments

Access patient list and medical records

Write and view prescriptions

Manage personal profile

🧑‍⚕️ Patient Dashboard
Book appointments with doctors

View medical history and prescriptions

Browse available doctors

Update settings and profile

🗂️ Project Structure
graphql
Copy
Edit
hospital-management-system/
│
├── app.py                     # Core Flask application and routes
├── database.db                # General SQLite database (if used)
├── database.py                # DB connection/initialization logic
├── patient.db                 # Patient-specific database
├── patient.py                 # Patient-related DB operations
├── prescription.db            # Prescription-specific database
├── prescription.py            # Prescription DB operations
│
├── templates/                 # HTML templates
│   ├── Login/                 # Login and Registration pages
│   ├── Doctor/                # Doctor-side pages
│   ├── Patient/               # Patient-side pages
│
├── static/                    # Static files
│   ├── styles.css             # Custom styles
│   ├── script.js              # JavaScript functionality
│   └── images/                # Image assets
⚙️ Installation & Setup
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/hospital-management-system.git
cd hospital-management-system
2. Create a Virtual Environment (Optional but recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Run the Application
bash
Copy
Edit
python app.py
Visit http://127.0.0.1:5000 in your browser to start using the app.

📦 Requirements
List of main Python packages:

nginx
Copy
Edit
Flask
sqlite3
You can generate requirements.txt with:

bash
Copy
Edit
pip freeze > requirements.txt
🖼️ Screenshots
Include a few screenshots of the UI here (doctor dashboard, patient dashboard, etc.)

📁 Databases
patient.db: Contains patient details

prescription.db: Stores prescription records

database.db: (Optional) General use or admin-related data

Ensure these databases are initialized before first use. You can add logic in database.py or a setup script to automate this.

☁️ Deployment
You can deploy this project on Render, Heroku, or PythonAnywhere.

Example Render start command:

nginx
Copy
Edit
gunicorn app:app
Make sure gunicorn is added to your requirements.txt.

🙌 Acknowledgements
Built with ❤️ using:

Flask

SQLite

Tailwind CSS

JavaScript

📜 License
This project is licensed under the MIT License.
