# Desktop-Windows-Application-Development
### **Task Description**

Create a WPF (Windows Presentation Foundation) application for managing user information stored in a database. The application should support basic CRUD operations, allowing users to perform the following tasks:

1. **View Users**: Display a list of all users in the database within a ListBox. Selecting a user should populate their details (username, password, and admin status) in the appropriate input fields.

2. **Add New User**:
   - Allow the creation of a new user by entering details in the input fields (username, password, and admin status).
   - Save the new user to the database.

3. **Edit User**:
   - Enable editing the selected user's details (username, password, and admin status).
   - Save the updated information back to the database.

4. **Database Integration**:
   - The user data should be stored in a database using Entity Framework Core.
   - The `User` table should include the following fields:
     - **ID**: Unique identifier for the user (Primary Key).
     - **UserName**: Name of the user.
     - **UserPass**: Password of the user.
     - **IsAdmin**: Boolean indicating whether the user is an administrator.

5. **UI Components**:
   - **ListBox**: To display the list of users.
   - **TextBox**: For entering or displaying the username.
   - **PasswordBox**: For entering or displaying the password.
   - **CheckBox**: To indicate whether the user is an administrator.
   - **Buttons**:
     - **Save**: To save changes to an existing user.
     - **Add**: To add a new user.

6. **Functionality**:
   - On selecting a user from the ListBox, their details should populate the input fields.
   - Modifying the input fields and clicking "Save" should update the user in the database.
   - Clicking "Add" should create a new user with the provided details and save it to the database.

---

