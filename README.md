# Phonebook-management-system

## Problem Statement:

By using Linked List:

A phonebook can be implemented as a linked list of data structures where each node may represent first name, last name and mobile number and you may also add addition nodes like e-mail, office no., address, etc for every contacts. You can make personal contact (name, mobile number, email, type) and professional contact list (name, mobile number, email, office number, address,institute/office, type). Keep the list sorted based on name. If names in two records are the same, then such records are to be ordered based on mobile number (by considering its integer value).
You need to provide a field according to which personal and professional contacts would be separate. (Type: personal/professional). In addition, such a phonebook should keep track of number of phone calls made to different contacts, the date and the duration of the calls.

The following functions/operations need to be implemented:
1. Insert/create contact:  
		a. A new contact to be inserted in the list. Make sure that there is no restriction for the contact with same name.  
		b. i/p: all the field related to insertion on a new contact  
		c. o/p: A message showing that contact is created  
2. Edit:  
		a. Edit option should be provided to modify the details.  
		b. i/p: all the fields that can be modified  
		c. o/p: message showing that contact in modified  
3. Delete:  
		a. contact can be deleted as a whole  
		b. i/p: field to search for contact that is to be deleted  
		c. o/p: message showing contact is deleted  
4. Search:  
		a. provide searching contact via name, mobile number and any other if you like  
		b. i/p: provide options to search using name and mobile no.  
		c. o/p: contact searched  
5. Sort:  
		a. Sorting in ascending /descending, professional/personal  
		b. i/p: Given unsorted list of records, provide the options for sorting i.e. using switch cases like ascending, descending.  
		c. o/p: sorted list according to the choice of user  
6. Display all:  
		a. Display personal list: only personal contacts to be displayed  
		b. Display professional list: only professional contacts to be displayed  
		c. i/p: option asking to show contacts  
		d. o/p: list as per option selected  
7. Union:  
		a. merge two linked lists sorted based on name and mobile number  
		b. i/p: Two linked lists sorted based on name and mobile number  
		c. o/p: A single linked list with union of records in two given linked lists, sorted based on name and mobile number  
8. Remove duplicates:  
		a. i/p: enter the list of records sorted based on name/mobile-number  
		b. o/p: linked list without duplicates  
9. Design a linked list that stores phonebooks of different people, that is we have to design linked list of linked lists. For each phonebook owner, we can keep minimum details like name, mobile number, address. From such a database, we need to display the names of people in the decreasing order of total time duration they have spoken to their own contacts.  


