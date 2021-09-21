### Address Book Management System

**Use case 1: Creating a single contact  **
[UC1_CreateContact](https://github.com/shruti2898/Address-Book-Management-System/blob/master/UC1_CreateContact.cs) class has only one method CreateContact() which will take input from user and appends them into a string named **contact** . Then it prints the contact string.


**Use case 2: Add new contacts into Address Book**
[UC2_AddNewContact](https://github.com/shruti2898/Address-Book-Management-System/blob/master/UC2_AddNewContact.cs) class has 4 methods. 
1.  AddNewContact() : entry point of this class.
2. CreateContact() : for creating new contacts and adding them into address book. And it will print all contacts that has been created.
3. ContactDetails() : for taking user inputs from console for a contact.
4. toContinue(): to ask user if he wants to continue adding contacts in address book.


**Use case 3: Updating existing contact into Address Book**
[UC3_UpdateExistingContact](https://github.com/shruti2898/Address-Book-Management-System/blob/master/UC3_UpdateExistingContact.cs) class has 5 methods. 
1.  UpdateContact() : entry point of this class. It will ask user whether he wants to create contact or update contact.
2. UpdateExistingContact() : firstly, it will check whether address book is empty or not.
  - If empty then we can add new contacts or simply exit from console app.
  - If it is not empty then it will ask for contact name for which we want to update contact details. And it will print all contacts that has been updated.
3. CreateContact() : for creating new contacts and adding them into address book. 
4. ContactDetails() : for taking user inputs from console for a contact.
5. toContinue(): to ask user if he wants to continue adding contacts in address book.

**Use case 4: Deleting existing contact from Address Book**
[UC4_DeleteContact](https://github.com/shruti2898/Address-Book-Management-System/blob/master/UC4_DeleteContact.cs) class has 5 methods. 
1.  ContactDelete() : entry point of this class. It will ask user whether he wants to create contact or delete contact.
2. DeleteExistingContact() : firstly, it will check whether address book is empty or not.
  - If empty then we can add new contacts or simply exit from console app.
  - If it is not empty then it will ask for contact name  which we want to remove from address book. And it will print all contacts that has been created.
3. CreateContact() : for creating new contacts and adding them into address book.
4. ContactDetails() : for taking user inputs from console for a contact.
5. toContinue(): to ask user if he wants to continue adding contacts in address book.
