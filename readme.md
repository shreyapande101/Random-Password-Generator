# Random Password Generator

The **Random Password Generator** is a simple web-based application that generates strong and secure passwords instantly.

This project is built using **HTML, CSS, and JavaScript** and focuses on practicing DOM manipulation, random value generation, and basic UI design.

---

## Features

- Generates a 12-character secure password
- Includes uppercase letters (A–Z)
- Includes lowercase letters (a–z)
- Includes numbers (0–9)
- Includes special symbols (@#$%^& etc.)
- One-click copy 
- Clean and modern interface

---

## Language Used

- **HTML** – Structure of the application
- **CSS** – Styling and layout design
- **JavaScript** – Password generation logic

---

## How It Works

- When the **Generate Password** button is clicked, the `createPassword()` function runs.
- The function ensures the password contains at least:
  - One uppercase letter
  - One lowercase letter
  - One number
  - One symbol
- The remaining characters are filled randomly.
- The generated password is displayed in the input field.
- Clicking the copy icon runs the `copyPassword()` function to copy the password to the clipboard.

---

## Personal Reflection

### What This Project Is

This is a beginner-friendly project that demonstrates how JavaScript can be used to create dynamic and practical tools. Even though it’s small, it combines structure, styling, and logic into one complete application.

---

### Why I Made It

I built this project to strengthen my understanding of:

- JavaScript fundamentals
- Random number generation
- Event handling
- Combining frontend technologies into one working project

---

### How I Made It

1. Created the layout using HTML.
2. Designed the interface using CSS with a clean and modern look.
3. Wrote JavaScript to:
   - Define character sets
   - Randomly select characters
   - Ensure password security rules
4. Added copy-to-clipboard functionality.

---

### What I Struggled With

- Making sure all character types are included in the password.
- Understanding how `Math.random()` works properly.
- Learning how clipboard copy functionality works.

---

### What I Learned

- How to generate random values in JavaScript.
- The importance of clean UI design.
- How small projects can build strong programming fundamentals.


