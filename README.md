BRD Laptop Support USSD System

This is a USSD-based application that allows RP students to:
- Register their student information
- Report laptop issues
- Check the status of their reported issues

The system uses PHP and MySQL and is integrated with an SMS module to notify users about registration and status updates.

 Developed By

- Umutesi Adelphine: – SMS Integration, Composer Packages, sms.php, Vendor Management  
- Ineza Gloria:–USSD Logic, Database Queries, and Flow Control

 Features

- USSD interface for user registration and support
- Issue reporting and tracking
- SMS notifications using sms.php module
- MySQL database for student and report data

  Setup Instructions:
1. Clone the repo and open in a PHP server environment (e.g., XAMPP).
2. Create the database using the brd_laptop_support.sql file.
3. Configure db.php with your DB credentials.
4. Host your USSD endpoint and link it in Africa’s Talking.
