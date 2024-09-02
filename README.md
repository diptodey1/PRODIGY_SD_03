Title: Python Contact Manager

Description:

This Python script provides a user-friendly contact management system. It allows you to create, view, edit, search, and delete contacts, storing them in a JSON file for persistence.

Installation:

Prerequisites: Ensure you have Python 3 installed on your system. You can download it from https://www.python.org/downloads/.

Clone the Repository: Use Git to clone this repository to your local machine:

Bash
git clone https://github.com/your-username/contact-manager   

Use code with caution.

Navigate to the Directory: Use the cd command to enter the project directory:

Bash
cd contact-manager
Use code with caution.

Usage:

Run the Script: Execute the script using the Python command:

Bash
python contact_manager.py
Use code with caution.

Features:

Add Contacts: Create new contacts by providing their name, phone number, and email address.
View Contacts: List all saved contacts with their information.
Edit Contacts: Modify existing contacts' details, including phone number and email address.
Search Contacts: Look up specific contacts by name.
Delete Contacts: Remove unwanted contacts from the contact list.
JSON File Storage: Contacts are persistently stored in a 'contacts.json' file for easy manipulation and retrieval.
Example Usage:

Adding a Contact:

-------------------------
Contact Manager Menu:
1. Add Contact
2. View Contacts
3. Edit Contact
4. Search a contact
5. Delete Contact
6. Exit
-------------------------

Enter your choice: 1

-------------------------
What's the person's name? John Doe
What's their phone number? 123-456-7890
What's their email address? john.doe@example.com

Contact John Doe added successfully!

-------------------------
Viewing Contacts:

-------------------------
Contact Manager Menu:
1. Add Contact
2. View Contacts
3. Edit Contact
4. Search a contact
5. Delete Contact
6. Exit
-------------------------

Enter your choice: 2

Name: John Doe, Phone Number: 123-456-7890, Email Address: john.doe@example.com
Editing a Contact:

-------------------------
Contact Manager Menu:
1. Add Contact
2. View Contacts
3. Edit Contact
4. Search a contact
5. Delete Contact
6. Exit
-------------------------

Enter your choice: 3

-------------------------
Whose details do you want to change? John Doe
New phone number (leave blank if no change): 555-123-4567
New email address (leave blank if no change):

Contact John Doe updated successfully!

-------------------------
Searching a Contact:

-------------------------
Contact Manager Menu:
1. Add Contact
2. View Contacts
3. Edit Contact
4. Search a contact
5. Delete Contact
6. Exit
-------------------------

Enter your choice: 4

-------------------------
Enter contact name to view: John Doe

Name=John Doe	Number=555-123-4567 (Updated phone number)

-------------------------
Deleting a Contact:

-------------------------
Contact Manager Menu:
1. Add Contact
2. View Contacts
3. Edit Contact
4. Search a contact
5. Delete Contact
6. Exit
-------------------------

Enter your choice: 5

-------------------------
Enter contact name to delete: John Doe

Contact John Doe deleted successfully!

-------------------------
Exiting the Script:

-------------------------
Contact Manager Menu:
1. Add Contact
2. View Contacts
3. Edit Contact
4. Search a contact
5. Delete Contact
6. Exit
-------------------------

Enter your choice: 6

-------------------------
Thanks for using our contact manager!
-------------------------
