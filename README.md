# contact management system 
This Contact Management System is a Python-based application designed to help users store, manage, and retrieve contact information efficiently. The system provides functionalities for adding, updating, deleting, and searching contacts, making it a simple yet powerful tool for organizing personal or professional contacts.

# Features:
Add Contact: Add new contacts with details like name, phone number, email, and address.
Update Contact: Modify the details of existing contacts.
Delete Contact: Remove contacts from the system.
Search Contact: Quickly search for a contact using keywords (e.g., name or phone number).
Display Contacts: View a list of all stored contacts in a readable format.
Data Persistence: Contact information is saved in a file (e.g., CSV or JSON), ensuring data is retained between sessions.
# Technologies Used:
Python: The primary programming language used for the application.
File Handling: Used to store contact information in CSV or JSON format.
Text-Based Interface: The system runs in the command line, providing a simple interface for user interaction.
# Requirements:
Python 3.x
Basic knowledge of Python programming and file handling.
Installation:
Clone the repository to your local machine:
bash
Copy
Edit
git clone https://github.com/your-username/Contact-Management-System-Project-in-Python.git
Navigate to the project directory:
bash
Copy
Edit
cd Contact-Management-System-Project-in-Python
Run the application:
bash
Copy
Edit
python contact_management.py
Example Usage:
python
Copy
Edit
# Add a new contact
>>> add_contact("John Doe", "1234567890", "john.doe@example.com", "123 Main St")

# Update an existing contact
>>> update_contact("John Doe", new_phone="0987654321")

# Search for a contact
>>> search_contact("John")

# Display all contacts
>>> display_contacts()
# License:
This project is open source and available under the MIT License.
