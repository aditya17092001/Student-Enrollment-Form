# Student-Enrollment-Form
Create a form based on any one of the TOPICS given below. The form should store data in the database. The primary key and input fields of each topic is mentioned.
There will be three control buttons [Save], [Update] and [Reset] at the bottom of the form. On page load or any control button click, an empty form will be displayed and the cursor will remain at the first input field in the form which will have the primary key in the relation. All other fields and buttons should be disabled at this time.
User will enter data in the field having primary key and
o If the primary key value does NOT exist in the database, enable [Save] and [Reset] buttons and move the cursor to the next field and allow the user to enter data in the form.
 Check that the data should be valid i.e. no empty fields.
 Complete the data entry form and click the [Save] button to store the data in the database and go to step-2.
o If the primary key value is present in the database, display that data in the form. Enable [Update] and [Reset] buttons and move the cursor to the next' field in the form. Keep the primary key field disabled and allow users to change other form fields.
 Check that the data should be valid i.e. no empty fields.
 Click on [Update] button to update the data in the database and go to step-2.
 Click [Reset] to reset the form as per the step-2.
Student Enrollment Form that will store data in STUDENT-TABLE relation of SCHOOL-DB database.
Input Fields: {Roll-No, Full-Name, Class, Birth-Date, Address, Enrollment-Date}
Primary key: Roll No.



A Student Enrollment Form is presented that stores information in the STUDENT-TABLE relation of the SCHOOL-DB database. Upon clicking the index.html Form, three buttons appear at the bottom of the form: [Save], [Update], and [Reset]. When the page loads or when a control button is clicked, an empty form will be displayed and the cursor will be placed in the first input field, which contains the primary key in the relation. All other fields and buttons will be disabled at this time. The user will enter data into the primary key field. If the primary key value does not exist in the database, the [Save] and [Reset] buttons will be enabled, the cursor will move to the next field, and the user will be able to enter data into the form. The data must be valid, meaning that no fields can be left empty. Once the data entry is complete, the user can click the [Save] button to store the information in the database and return to step 2. If the primary key value is already present in the database, the corresponding data will be displayed in the form. The [Update] and [Reset] buttons will be enabled, the cursor will move to the next field, and the primary key field will be disabled. The user can then edit the other fields in the form. As before, the data must be valid, meaning that no fields can be left empty. Once the user is finished editing the data, they can click the [Update] button to save the changes to the database and return to step 2. The [Reset] button will clear the form as per step 2.
