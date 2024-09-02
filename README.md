Manage Your Contacts Efficiently: A Python Contact Manager
This Python script provides a user-friendly contact manager application that allows you to add, view, edit, search, and delete contacts from a JSON file. It offers a convenient way to organize your contact information and keep it readily accessible.

Core Functionality:

Contact Class: The script defines a Contact class to represent each contact with attributes for name, phone number, and email address.
Contact Manager Class: The ContactManager class acts as the central hub for managing contacts. It handles tasks like loading and saving contacts to a JSON file (contacts.json by default) and interacting with individual contacts.
User Interaction: The script utilizes a main function that creates an instance of the ContactManager class and presents a menu-driven interface to the user.
Menu Options: Users can choose from various options:
Add Contact: Creates a new contact and adds it to the list with name, phone number, and email details.
View Contacts: Displays a list of all saved contacts or indicates if none exist.
Edit Contact: Allows users to modify specific details (phone number or email) of an existing contact based on their name.
Search a contact (New Feature): Enables searching for a specific contact by name, displaying their contact information if found.
Delete Contact: Removes a contact from the list by entering their name.
Exit: Gracefully terminates the program.
Data Persistence:

JSON File: The contact information is stored and retrieved from a JSON file, ensuring data persistence between program executions.
Loading and Saving: The ContactManager class handles loading contacts from the JSON file during initialization and saving any changes back to the file after successful operations (add, edit, delete).
Error Handling:

Missing File: If the contacts.json file is absent at startup, the script creates an empty list for contacts.
Contact Not Found: When searching or editing contacts that don't exist, the script provides informative messages.
Invalid User Input: The menu loop validates the user's choices to prevent invalid options and ensures smooth program flow.
Overall Benefits:

This script offers a valuable tool for managing personal or professional contacts. It's well-structured, uses clear variable and function names, and includes comments for better understanding. The addition of a search functionality makes finding specific contacts even faster.
