# DOM Array Methods Project

A simple interactive web application built using **HTML, CSS, and JavaScript** to demonstrate how common **JavaScript array methods** work together with **DOM manipulation**.

This project visually displays users with random wealth values and allows different operations such as doubling money, filtering millionaires, sorting by wealth, and calculating total wealth.

---

## 📌 Features

- Add random users with generated wealth
- Double the money of all users
- Show only users who are millionaires
- Sort users by richest first
- Calculate total combined wealth
- Dynamic DOM updates without page reload

---

## 🧠 Concepts Used

### JavaScript
- `map()` – to double user money
- `filter()` – to show only millionaires
- `sort()` – to arrange users by wealth
- `reduce()` – to calculate total wealth
- `forEach()` – to render data on the DOM
- DOM manipulation (`querySelector`, `createElement`, `innerHTML`)
- Event handling (`addEventListener`)
- Fetch API (Random User API)

### HTML & CSS
- Semantic HTML structure
- Flexbox layout
- Responsive design using media queries
- Clean and minimal UI styling

---

## 🗂️ Project Structure
```
DOM-Array-Methods
│
├── index.html
├── style.css
└── script.js
```

---

## ⚙️ How It Works

1. On page load, three random users are fetched automatically.
2. Each user is assigned a random wealth value.
3. Buttons trigger different array operations:
   - **Add User** → Fetches a new random user
   - **Double Money** → Uses `map()`
   - **Show Only Millionaires** → Uses `filter()`
   - **Sort by Richest** → Uses `sort()`
   - **Calculate Entire Wealth** → Uses `reduce()`
4. The DOM updates instantly after every operation.

---

## 🖥️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Random User API

---

## 🎯 Learning Outcome

This project helped in understanding:
- Practical usage of JavaScript array methods
- Real-time DOM updates

---

## 📄 License

This project is for **educational purposes only**.
