Terms of reference.

Development of a class system for address book management.

Entities:

 - Field: Base class for record fields. It will be the parent for all fields, it implements the logic common to all fields
 - Name: Class for storing the name of the contact. Required field.
 - Phone: A class for storing a phone number. Has format validation (10 digits). The phone field is optional and one Record record can contain several of them.
 - Record: A class for storing information about a contact, including the name and phone list. Responsible for the logic of adding/deleting/editing optional fields and storing the required Name field
 - AddressBook: A class for storing and managing records. It is inherited from UserDict and contains the logic for searching for records in this class

Functionality:

1. AddressBook:
 - Adding records.
 - Search for records by name.
 - Deleting records by name.
2. Record:
 - Add phone numbers.
 - Delete phone numbers.
 - Edit phone numbers.
 - Search for a phone.
