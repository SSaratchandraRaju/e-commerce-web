# 🛒 E-Commerce Website

A responsive, multi-page e-commerce website project built using HTML, CSS, and JavaScript. This project simulates a basic online store experience with product listings, categorization, shopping cart functionality, and a checkout interface.

---

## 📁 Project Structure

```
E-COMMERCE/
│
├── assets/                     # Static files like images or icons (optional)
│
├── cart/                       # Cart-specific files
│   ├── cart.css                # Styling for cart page
│   ├── cart.html               # HTML structure for the cart page
│   └── cart.js                 # JS logic for cart operations
│
├── checkout/                   # Checkout-specific files
│   ├── checkout.css            # Styling for checkout page
│   ├── checkout.html           # HTML structure for checkout page
│   └── checkout.js             # JS logic for checkout processing
│
├── .vscode/                    # Editor-specific settings (if any)
│
├── index.html                  # Main homepage with navigation and product categories
├── notification.js             # Handles notifications or alerts
├── ProductsData.json           # Static product data in JSON format
├── script.js                   # Main JavaScript file for general page interactions
├── style.css                   # Global stylesheet
```

---

## 🌐 Features

* **Home Page with Navigation Bar**
  Categories such as Electronics, Fashion, Furniture, etc., linked using query parameters.

* **Product Filtering by Category**
  Products are dynamically filtered based on the category from `ProductsData.json`.

* **Shopping Cart**

  * Add/remove items from the cart.
  * Cart item counter updates in real-time.
  * View cart details on `cart.html`.

* **Checkout Page**

  * Displays selected cart items.
  * Placeholder for payment integration.

* **Responsive Design**

  * Built with mobile-first principles.
  * Uses external libraries like [Swiper.js](https://swiperjs.com/) for carousels.

* **Fonts & Icons**

  * Uses Google Fonts (`Playfair Display`, `Montserrat`) and Font Awesome icons.

---

## 🔧 Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/SSaratchandraRaju/e-commerce-web.git
   cd e-commerce-site
   ```

2. **Open the project**

   * Open `index.html` in a web browser.
   * Use Live Server for a better development experience in VS Code.

---

## 🔗 External Libraries

* **[Swiper.js](https://swiperjs.com/)** – For interactive sliders and carousels.
* **[Font Awesome](https://fontawesome.com/)** – For cart and UI icons.
* **[Google Fonts](https://fonts.google.com/)** – Typography customization.

---

## 📦 Data Handling

* Product data is stored in `ProductsData.json` and dynamically loaded using JavaScript.
* Filtered on category selection via query parameters (`?category=electronics`, etc.).

---

## 📌 Future Enhancements

* Add local storage support to persist cart items.
* Integrate a real payment gateway (e.g., Stripe).
* Implement user authentication.
* Add search and sorting functionality for products.

---

## 🧑‍💻 Author

**Saratchandra Raju Sarikonda**
[GitHub Profile](https://github.com/SSaratchandraRaju/)
[LinkedIn](https://www.linkedin.com/in/s-saratchandra-raju/)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
