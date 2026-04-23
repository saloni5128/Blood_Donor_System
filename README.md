LifeLink – Blood Donor Management System
________________________________________
Project Description
LifeLink is a Python-based Blood Donor Management System built using Tkinter and SQLite.
It helps manage donor records, track donation history, and quickly find suitable donors during emergencies.
The system includes smart eligibility checking (90-day rule), rare blood group identification, and automatic PDF certificate generation for donors.
________________________________________
Features
•	Donor Registration with validation 
•	Smart Blood Group Search 
•	Location-Based Donor Search 
•	Emergency Blood Request Management 
•	Donor Availability Tracking 
•	Donation History Management (Add / Update / Delete) 
•	Eligibility Check (based on last donation date) 
•	Rare Blood Group Highlighting 
•	Automatic PDF Certificate Generation 
•	Clean Tkinter UI with scrollable tables 
________________________________________
Workflow
1.	Donors are registered with personal and medical details. 
2.	The system checks eligibility using the 90-day donation rule. 
3.	Donors can be searched by blood group or location. 
4.	Emergency requests can be created for urgent needs. 
5.	Donation records are stored and updated dynamically. 
6.	A PDF certificate is automatically generated after donation. 
7.	The system highlights rare blood groups for priority handling. 
________________________________________
Project Structure
Blood_Donor_System/
│
├── main.py
├── README.md
│
├── core/
│   ├── database.py
│   ├── utils.py
│   └── theme.py
│
├── modules/
│   ├── admin/
│   │   └── admin_module.py
│   │
│   ├── donor/
│   │   ├── donor_registration.py
│   │   ├── donor_availability.py
│   │   └── donation_history.py
│   │
│   ├── search/
│   │   ├── blood_search.py
│   │   └── location_search.py
│   │
│   └── emergency/
│       └── emergency_request.py
│
├── services/
│   └── certificate_utils.py
│
├── ui/
│   └── dashboard.py
│
├── assets/
│   └── certificates/
│
└── data/
    └── blood_donor_system.db
________________________________________
Tech Stack
•	Python 
•	Tkinter (GUI) 
•	SQLite (Database) 
•	ReportLab (PDF generation) 
________________________________________
Installation & Run
# 1) Open terminal in project folder
cd Blood_Donor_System

# 2) Install dependencies
pip install reportlab

# 3) Run the application
python main.py
________________________________________
How to Use
1.	Register a new donor 
2.	Search donors using blood group or location 
3.	Create emergency requests 
4.	Track donor availability 
5.	Add donation history 
6.	Generate and view certificates 
________________________________________
Demo
Project Demo Video:
https://drive.google.com/file/d/1LwbLW5OY_3UXN-IPPGJStDMRBulhQXev/view?usp=sharing
________________________________________
Team Contribution
•	Prachi Ghoghari (Core Development) 
o	Database design (SQLite)
o	Tkinter UI design & layout   
•	Neel Bagwale (Feature Development) 
o	Blood search & location-based search 
o	Donor availability module 
•	Saloni Dighe (Advanced Features)  
o	Emergency request handling 
o	Certificate generation (PDF using ReportLab) 
o	Eligibility logic & smart enhancements
________________________________________
Conclusion
LifeLink provides an efficient and user-friendly solution for managing blood donors.
It can be extended into a real-world healthcare system with features like cloud integration and real-time notifications.
