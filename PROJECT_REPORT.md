# Project Report: FreshBite — Online Food Ordering

**Task ID:** WD-EC-001  
**Domain:** Web Development / Food & Restaurant E-Commerce

## 1. Objective
The objective of FreshBite is to build a responsive, user-friendly food-ordering website that demonstrates the core flow of a small food e-commerce application. Visitors can explore dishes and restaurant listings, search and filter menu items, manage a shopping basket, and complete a simulated checkout.

## 2. Technologies Used
- **HTML5:** semantic page structure, navigation, menu, forms, and content sections.
- **CSS3:** responsive layouts, design tokens, cards, hover effects, mobile navigation, and reduced-motion support.
- **JavaScript:** menu rendering, search and dietary filters, cart and quantity management, pricing, coupon validation, form validation, simulated checkout, wishlist, and profile/order history.
- **LocalStorage:** saves demo cart, wishlist, profile, and order history in the current browser.

## 3. Main Features
1. Home page with brand identity, call-to-action, food categories, and promotional coupon.
2. Restaurant listing cards with cuisine, ratings, and estimated delivery times.
3. Food menu with dish descriptions, prices, ratings, category labels, search, and dietary filters.
4. Shopping basket with add/remove via quantity controls, subtotal, delivery charge, discount, and total.
5. Checkout form for customer name, phone, delivery address, delivery time, and a simulated payment choice.
6. Demo order confirmation and local order history.
7. Demo profile, wishlist, About Us, and Contact Us sections.
8. Responsive design for common desktop, tablet, and mobile screen sizes.

## 4. How It Works
Food items are represented as JavaScript objects in an array. The page dynamically renders cards from this data. Cart rows store item IDs and quantities; totals are calculated from menu prices. The `FIRSTBITE` coupon applies a 10% demo discount. On checkout, the form is validated in the browser, an order summary is saved locally, and the cart is cleared. No network request, real payment, or server-side account is involved.

## 5. Learning Outcomes
This project provides practice with semantic HTML, CSS Grid and Flexbox, media queries, DOM manipulation, event handling, array methods, form validation, data persistence with LocalStorage, and building an end-to-end frontend interaction flow.

## 6. Limitations and Future Improvements
The application is frontend-only. Authentication, payment, restaurant availability, delivery tracking, and contact submission are simulated. Future improvements could add a backend API, database, secure authentication, live restaurant data, map integration, order status updates, and a payment provider in a controlled test environment.

## 7. Testing Plan
- Verify navigation links and mobile menu.
- Search for dishes and check category/diet filters.
- Add multiple dishes, adjust quantities, and remove items.
- Confirm subtotal, delivery fee threshold, coupon, and total.
- Submit checkout with valid and invalid fields; verify empty-cart protection.
- Check wishlist, profile, and order history after page refresh.
- Test desktop and mobile widths and confirm no horizontal overflow.
- Confirm the project never claims to process real payments or send contact messages.
