# Desktop-Windows-Application-Development
### **Task: Creating a Calculator Using WPF**

Create a calculator application using WPF (Windows Presentation Foundation). The application should support basic arithmetic operations and provide interaction through buttons on a graphical user interface. Follow the requirements below:

---

### **Requirements**:

1. **User Interface (UI)**:
   - Design the calculator layout using XAML.
   - Include:
     - A display area (e.g., `TextBlock`) to show the current input and results.
     - Buttons for numbers (`0-9`).
     - Buttons for basic operations (`+`, `-`, `×`, `÷`, and `=`).
   - Organize the buttons in a grid layout.

2. **Functionality**:
   - Clicking number buttons (`0-9`) should update the display with the corresponding digit.
   - Clicking an operation button (`+`, `-`, `×`, or `÷`) should:
     - Save the current input.
     - Clear the display for the next number.
     - Store the selected operation.
   - Clicking the `=` button should:
     - Perform the selected operation.
     - Display the result in the output area.

3. **Logic Implementation**:
   - Use event handlers in the code-behind file (C#) to handle button clicks.
   - Implement logic for each operation (`addition`, `subtraction`, `multiplication`, `division`).
   - Handle division by zero appropriately (e.g., show an error message or `Infinity`).

4. **Optional Features** (for extra credit):
   - Add a `Clear` button to reset the calculator.
   - Allow chaining of operations without clearing the result.
   - Improve the visual design with colors and styles.

---

### **Example**:
- Input: User clicks `7`, `+`, `3`, `=`.
- Output: Display shows `10`.

