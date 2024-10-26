## Frontend Developer Interview Questions (Ena Ema Technology Limited)

### Question 1: Shopping Cart Calculation
**Problem Statement:**  
You are working on the shopping cart functionality for an online store. Write a function called `calculateCartTotal` that takes an array of items in the cart. Each item has a `price`, `quantity`, and an optional `discount` percentage. The function should return the total price of the cart after applying the discount to each item.

#### Sample Data
```javascript
const cartItems = [
  { price: 10.0, quantity: 2, discount: 0 },
  { price: 15.0, quantity: 1, discount: 10 }, // 10% discount
  { price: 20.0, quantity: 3, discount: 5 }   // 5% discount
];
```

#### Expected Output
```javascript
// Total = (10 * 2) + (15 * 1 * 0.9) + (20 * 3 * 0.95) = 20 + 13.5 + 57 = 90.5
90.5
```

#### Function Signature
```javascript
function calculateCartTotal(cart) {
  // Your code here
}
```

---

### Question 2: User Authentication Token
**Problem Statement:**  
You are developing a user authentication system for a web application. Write a function called `generateAuthToken` that takes a user object containing `userId`, `username`, and `role`, and returns a JSON Web Token (JWT) string. For simplicity, you can mock the token generation by returning a concatenated string of the user properties.

#### Sample Data
```javascript
const user = {
  userId: '12345',
  username: 'john_doe',
  role: 'admin'
};
```

#### Expected Output
```javascript
'12345.john_doe.admin'
```

#### Function Signature
```javascript
function generateAuthToken(user) {
  // Your code here
}
```

---

### Question 3: Form Data Serialization
**Problem Statement:**  
You are creating a form submission feature for a web application. Write a function called `serializeFormData` that takes an object representing form fields and their values and returns a query string format suitable for URL encoding.

#### Sample Input
```javascript
const formData = {
  name: 'Jane Doe',
  email: 'jane@example.com',
  age: 28,
  interests: ['reading', 'traveling']
};
```

#### Expected Output
```javascript
'name=Jane%20Doe&email=jane%40example.com&age=28&interests=reading&interests=traveling'
```

#### Function Signature
```javascript
function serializeFormData(data) {
  // Your code here
}
```
