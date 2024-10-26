<h3 align="center"> Frontend Developer Interview Questions (Ena Ema Technology Limited)</h3>

### Question 1: Shopping Cart Calculation

**Problem Statement:**  
You are working on the shopping cart functionality for an online store. Write a function called `calculateCartTotal` that takes an array of items in the cart. Each item has a `price`, `quantity`, and an optional `discount` percentage. The function should return the total price of the cart after applying the discount to each item.

**Sample Data:**
```javascript
const cartItems = [
  { price: 10.0, quantity: 2, discount: 0 },
  { price: 15.0, quantity: 1, discount: 10 }, // 10% discount
  { price: 20.0, quantity: 3, discount: 5 }   // 5% discount
];
```

**Expected Output:**
```javascript
// Total = (10 * 2) + (15 * 1 * 0.9) + (20 * 3 * 0.95) = 20 + 13.5 + 57 = 90.5
90.5
```

**Function Signature:**
```javascript
function calculateCartTotal(cart) {
  // Your code here
}
```

---

### Question 2: Expense Tracker

**Problem Statement:**  
You are creating an expense tracker application for users to log their daily expenses. Write a function called `calculateTotalExpenses` that takes an array of expense objects and returns the total amount spent. Each expense object has a `description` and an `amount`.

**Example Input:**
```javascript
const expenses = [
  { description: 'Groceries', amount: 50 },
  { description: 'Gas', amount: 30 },
  { description: 'Rent', amount: 1000 },
  { description: 'Utilities', amount: 150 }
];
```

**Expected Output:**
```javascript
1230
```

---

### Question 3: Library Book Search

**Problem Statement:**  
You are developing a library management system where users can search for books. Write a function called `searchBooks` that accepts an array of book objects and a search term. The function should return an array of book titles that include the search term (case-insensitive).

**Example Input:**
```javascript
const books = [
  { title: 'The Great Gatsby', author: 'F. Scott Fitzgerald' },
  { title: 'To Kill a Mockingbird', author: 'Harper Lee' },
  { title: '1984', author: 'George Orwell' },
  { title: 'The Catcher in the Rye', author: 'J.D. Salinger' }
];
const searchTerm = 'the';
```

**Expected Output:**
```javascript
['The Great Gatsby', 'The Catcher in the Rye']
```

---

### Question 4: Simple Voting System

**Problem Statement:**  
You are building a simple voting system for a local election. Write a function called `tallyVotes` that takes an array of votes, where each vote is represented as a string of a candidate's name. The function should return an object that shows each candidate's name and the number of votes they received.

**Example Input:**
```javascript
const votes = [
  'Alice',
  'Bob',
  'Alice',
  'Charlie',
  'Bob',
  'Alice'
];
```

**Expected Output:**
```javascript
{
  Alice: 3,
  Bob: 2,
  Charlie: 1
}
```
