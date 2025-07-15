# Calculator
Features:
Fully functional calculator with:

Addition (+)

Subtraction (−)

Multiplication (×)

Division (÷)

Decimal point support

Double zero (00) input

AC button to clear all input.

DE button to delete the last character (Backspace).

Result (=) button to evaluate the expression using JavaScript's eval() function.

🧱 Technologies Used:
HTML for the structure of the calculator.

CSS for styling the layout, colors, and button design (neumorphism-style shadows).

JavaScript (inline) for handling button click actions and evaluating expressions.

🖥️ UI Design Highlights:
Neumorphism effect on buttons using box shadows for a modern soft UI.

Calculator container is centered vertically and horizontally using Flexbox.

Custom styling for operator buttons (+, −, ×, ÷, =, AC, DE) to differentiate from number buttons.

⚙️ Functionality Overview:
Each button has an onclick event that updates the display.value:

Digits & operators append characters to the display.

AC clears the display entirely.

DE removes the last character using .slice().

= evaluates the expression using eval() and shows the result.

⚠️ Note:
Using eval() is acceptable for simple learning projects but not safe for production use, as it can lead to security vulnerabilities if used with untrusted input.

✅ Ideal For:
Beginners learning HTML/CSS/JavaScript.

Practicing DOM manipulation and event handling.

Understanding basic calculator logic and layout design.

Would you like a version with external JavaScript and CSS files separated for cleaner structure?









Ask ChatGPT
