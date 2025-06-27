# 🛒 Ecommerce Cards and Wishlist - Simple JS Alert Project

This is a **simple and minimalistic eCommerce UI project** built using **HTML**, **CSS**, and **JavaScript**, where two interactive buttons — `Add to Cart` and `Wishlist ❤️` — display simple alert messages on click.

> 🔔 Perfect for beginners learning DOM manipulation and event handling.

---

## 🧱 Project Structure

📁 ecommerce-alert-ui
├── index.html # Main HTML file
├── style.css # Styling for layout and buttons
├── index.js # JavaScript alert logic
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🚀 Features

- ✅ Clean layout using Flexbox
- ✅ Responsive button design
- ✅ Alert functionality with JavaScript
- ✅ Beginner-friendly structure
- ✅ Easily expandable for real eCommerce logic

---

## 🧠 How It Works

### ✅ HTML (`index.html`)

```html
<main>
  <h1>Eccommerce Cards And Wishlist</h1>
  <div class="container">
    <button class="cart">Add To Cart</button>
    <button class="wishlist">❤️ Wishlist</button>
  </div>
</main>
Contains a simple header and two action buttons inside a styled container.

🎨 CSS (style.css)
css
Copy
Edit
.container {
  width: 30vw;
  margin: auto;
  background: rgba(232, 232, 232, 0.632);
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.06);
  display: flex;
  justify-content: center;
  min-height: 20vh;
  align-items: center;
  gap: 1rem;
}

.cart {
  padding: 0.5rem 1.1rem;
  border: none;
  background: rgb(119, 161, 35);
  color: white;
  border-radius: 5px;
  cursor: pointer;
}

.wishlist {
  padding: 0.5rem 1.1rem;
  border: none;
  background: rgba(181, 126, 24, 0.851);
  color: white;
  cursor: pointer;
  border-radius: 5px;
}

h1 {
  text-align: center;
}
Utilizes Flexbox for alignment and spacing.

Buttons are styled differently for better UX.

⚙️ JavaScript (index.js)
javascript
Copy
Edit
const cart = document.querySelector(".cart");
const wishlist = document.querySelector(".wishlist");

cart.addEventListener("click", () => {
  alert("Item added to cart");
});

wishlist.addEventListener("click", () => {
  alert("Item added to wishlist");
});
Uses querySelector to grab buttons.

Adds simple click event listeners to show alerts.
