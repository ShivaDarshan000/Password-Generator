# Password-Generator

A sleek, responsive password generator built with **HTML, CSS, and Vanilla JavaScript**.  
Pick the length, choose character sets (uppercase, lowercase, numbers, symbols), generate a password, and copy it with one click. Strength indicator updates in real time.

---

##  Screenshot
<img width="1191" height="851" alt="image" src="https://github.com/user-attachments/assets/14ef52ff-d3f0-4e8a-b262-ac008dd0416d" />


---

##  Features

- Adjustable length (1–20) with a smooth, filled slider
- Character set toggles: **Uppercase**, **Lowercase**, **Numbers**, **Symbols**
- Guarantees at least one character from each selected set
- **Copy to clipboard** with tooltip feedback
- **Strength indicator** (Weak / Medium / Strong) via color dot
- Mobile-friendly UI with custom theme using CSS variables

---

##  Tech Stack

- **HTML5** for structure  
- **CSS3** (custom properties, gradients, styled slider, custom checkboxes)  
- **JavaScript (ES6+)** for logic (Fisher–Yates shuffle, generators, clipboard API)

---

 How to Use

Move the Password Length slider to choose length.

Check the boxes for the character types you want.

Click Generate Password.

Click the copy button to copy it to your clipboard (tooltip shows status).

Note: If you select multiple character types, the generator guarantees at least one character from each selected type and shuffles the result for randomness.

---

 Strength Indicator

The circular indicator reflects strength based on:

Inclusion of upper + lower and either numbers or symbols

Length thresholds (≥6 for medium, ≥8 for strong)

Colors:

🟥 Red — Weak

🟨 Yellow — Medium

🟩 Green — Strong

  
