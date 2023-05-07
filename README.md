Download Link: https://assignmentchef.com/product/solved-pet-database
<br>
Please include the questions with your answers. Answer in complete sentences where applicable.

<ol>

 <li>Does all standard SQL work in Microsoft Access? Explain.</li>

 <li>List and describe the four basic SQL data types.</li>

 <li>List and describe five SQL built-in functions.</li>

</ol>

The best way to learn SQL is by actually using it. In the following problems, we will use SQL to create, populate, and query a small database. Use SQL in Microsoft Access to complete the problems. Save all queries as instructed in the problem. Submit the database file (save as Pet_Database.accdb and KEEP THIS FILE for use with a later assignment) with all your queries in addition to the Word document containing the questions and answers for numbers 1, 2, and 3.

Use the following information for problems 4 – 10:

Tables:

PET_OWNER (OwnerID, OwnerLastName, OwnerFirstName, OwnerPhone, OwnerEmail)

PET (PetID, PetName, PetType, PetBreed, PetDOB, OwnerID)

**Note: OwnerID is italicized to indicate the Foreign Key**

Data:

<ol start="4">

 <li>Write an SQL CREATE TABLE statement to create the PET_OWNER table, with OwnerID as a surrogate key. Save as CreatePetOwner.</li>

 <li>Write a set of SQL INSERT statements to populate the PET_OWNER table with the data given above. Save as PopulatePetOwner.</li>

 <li>Write an SQL CREATE TABLE statement to create the PET table, with PetID as a surrogate key. Save as CreatePet.</li>

 <li>Write a set of SQL INSERT statements to populate the PET table with the data given above. Save as PopulatePet.</li>

 <li>Write an SQL statement to display the breed and type of all pets. Save as AllBreeds.</li>

 <li>Write an SQL statement to display the breed, and DOB of all pets having the type Cat. Save as Cats.</li>

 <li>Write an SQL statement to display the first name, last name, and email of all owners, sorted in alphabetical order by last name. Save as AlphaOwners.</li>

 <li>Write an SQL statement to display all the owners’ names, with the first name in all lower case and the last name in all upper case. Save as UpperLower.</li>

 <li>Write an SQL statement to display the total number of pets. Save as TotalPets.</li>

 <li>Write an SQL statement to display the last name, first name and email of any owner who has a NULL value for OwnerPhone. (Note: there should be one owner who has a NULL value for OwnerPhone.) Save as PhoneNull.</li>

 <li>Write an SQL statement to count the number of distinct breeds. Save as NumberOfBreeds.</li>

 <li>Write an SQL statement to display the names of all the dogs. Save as Dogs.</li>

</ol>




Part A and Part B are separate; please provide Separate files for each.

<ul>

 <li><strong>Part B</strong>: Use the Week 3 Assignment Pet_Database File for this section of the assignment. In the PET table, delete the PetDOB field and add a numeric PetCost field. Populate this field with appropriate values. Save the changes to the PET table. Create SQL queries to do the following:

  <ul>

   <li>Display the last name and phone number of all dog owners. Use a subquery to do this.</li>

   <li>Display the first and last name of owners and the type of animal of all unknown breeds.</li>

   <li>Display the pet name and owner last name of all dogs.</li>

  </ul></li>

</ul>

Save all 3 queries.

Export the PET table to an Excel spreadsheet. Create a Pivot table. Have the cost display as currency. Take screen shots* of two different views without a report filter and paste the screen shots into a Word document. Then add a report filter and choose one value for it, take a screen shot, then choose a different value for the same filter and take another screen shot. Paste those into the Word document containing the first two screen shots. You should now have 4 screen shots in this Word document. Save the Word document as Screen shots. Save the pivot table as Pivot.





