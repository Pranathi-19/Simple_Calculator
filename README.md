# Simple Calculator

A basic web-based calculator built with HTML, JavaScript, and minimal styling.  
This project allows the user to perform **addition, subtraction, multiplication, and division** with real-time validation.

---

## 📝 Features

- Perform addition, subtraction, multiplication, and division.
- Input validation: only numbers are allowed.
- Prevents division by zero.
- Displays results dynamically on the page.
- Includes an `outputs` folder with screenshots demonstrating each operation.

---

## 📂 Project Structure
Simple_Calculator/
│
├─ simple_Calculator.html # Main HTML file
├─ outputs/ # Screenshots of calculator results
│ ├─ addition.png
│ ├─ subtraction.png
│ ├─ multiplication.png
│ ├─ division.png
│ └─ divisionByZero.png

---

## ⚡ How to Use

1. Open `simple_Calculator.html` in any modern web browser.
2. Enter two numbers in the input fields.
3. Click on the desired operator (`+`, `-`, `*`, `/`) to perform the calculation.
4. The result will appear below the buttons.

---

## 💻 Example Usage

- Enter `10` and `5` → Click `+` → Result: `Addition of the numbers is: 15`
- Enter `10` and `0` → Click `/` → Result: `Division by zero is not allowed`

Screenshots for each operation are provided in the `outputs/` folder.

---

## 🛠️ Implementation Details

The calculator uses two main functions in JavaScript:

1. **`validation(operator)`**  
   - Checks if both inputs are numbers.  
   - Calls `calculate(operator)` if valid.

2. **`calculate(operator)`**  
   - Performs the calculation based on the operator.  
   - Updates the result in the `<h4>` element with `id="result_id"`.  
   - Handles division by zero gracefully.

---

## 🎨 Demo Screenshots

All screenshots demonstrating the calculator operations are inside the `outputs` folder:

- `addition.png`  
- `subtraction.png`  
- `multiplication.png`  
- `division.png`  
- `divisionByZero.png`

---

## 📝 Notes

- Works in all modern browsers.  
- No external libraries are required.  
- Ideal for learning basic JavaScript DOM manipulation and event handling.
