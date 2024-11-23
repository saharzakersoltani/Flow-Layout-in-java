# Simple Border Layout in java

This Java program demonstrates the creation of a GUI using Swing, showcasing how to arrange components in a `JPanel` and manage its layout. The application creates a `JFrame` with a single `JPanel` containing eight buttons, demonstrating basic layout management with `FlowLayout`. The JPanel also has a customizable background color to enhance visual appearance.

The program is a great starting point for beginners learning Java Swing or anyone exploring how to organize and arrange components in a simple desktop application.

-----------

## Features

- Customizable Panel: The `JPanel` has a pink background and can easily be modified for other preferences.
- Buttons with Focus Disabled: All buttons have `setFocusable(false)` applied to ensure a cleaner user experience.
- Resizable Window: The main `JFrame` is resizable, allowing users to see how the layout adapts.
- Flow Layout: Demonstrates the use of `FlowLayout` to align components neatly in a row or flow to the next line as space allows.

-------------

## Preview

The application features:

- A main window (JFrame) with size 500x500.
- A centered panel (JPanel) of size 300x350, with a pink background.
- Eight buttons neatly aligned within the panel.

-----------------------

## Requirements

- Java Version: Java 17 or higher (as per modern Java standards and features).
- Maven: Optional, but useful if you are building and managing dependencies.

----------------------

## Getting Started

1- Clone the repository:
```bash
git clone https://github.com/yourusername/YourRepositoryName.git
```

2- Navigate to the project directory:
```bash
cd Flow-Layout-in-java
```

3- Compile the program:
```bash
javac Main.java
```

4- Run the program:
```bahs
java Main
```

--------------------

## Customization

You can customize the program to suit your needs:

1- Change the Background Color: Modify the line:
```bash
panel.setBackground(Color.pink);
```
Replace `Color.pink` with another color, e.g., `Color.blue` or `new Color(255, 200, 200)`.

2- Add More Components: Add more Swing components (e.g., labels, text fields) to the panel:
```bash
panel.add(new JLabel("My Label"));
panel.add(new JTextField(10));
```

3- Change Layout: Replace `FlowLayout` with other layouts like `GridLayout` or `BorderLayout`:
```bash
panel.setLayout(new GridLayout(2, 4)); // 2 rows, 4 columns
```
------------

## Example Output

When you run the program, you’ll see a window with:

- A pink panel centered within the frame.
- Eight buttons aligned in rows as space allows.







  
