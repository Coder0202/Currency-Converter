# Currency-Converter
This Java program creates a simple currency converter using Java Swing to convert between Indian Rupees (INR) and US Dollars (USD).

Here’s a detailed breakdown of what it does:

1. Purpose
Converts Rupees → Dollars and Dollars → Rupees using fixed exchange rate (1 USD = 80.25 INR).

Provides a graphical user interface (GUI) for easy interaction.

2. GUI Components
Frame:
JFrame f → The main application window titled "CONVERTER".

Labels:

l1 → Displays "Rupees:"

l2 → Displays "Dollars:"

Text Fields:

t1 → Input/output box for Rupee values (default 0).

t2 → Input/output box for Dollar values (default 0).

Buttons:

b1 (INR) → Converts Rupees from t1 into Dollars and shows result in t2.

b2 (Dollar) → Converts Dollars from t2 into Rupees and shows result in t1.

b3 (close) → Closes the converter window.

3. Event Handling (Action Listeners)
INR Button (b1):

Reads number from t1 (Rupees).

Divides by 65.25 to get Dollars.

Displays result in t2.

Dollar Button (b2):

Reads number from t2 (Dollars).

Multiplies by 65.25 to get Rupees.

Displays result in t1.

Close Button (b3):

Calls f.dispose() to close the window.

Window Close (X button):

Calls System.exit(0) to exit the application completely.

4. Layout & Appearance
Absolute positioning (setBounds) for each component — no layout manager used (setLayout(null)).

Window size is 400 × 300 pixels.

Window is visible after setVisible(true).

5. How It Works
Program starts → main() calls converter().

GUI is displayed.

User enters a value in either Rupees or Dollars field.

Click the respective button to convert the currency.

Result appears in the other text field.

User can close the window using "close" button or the window's X
