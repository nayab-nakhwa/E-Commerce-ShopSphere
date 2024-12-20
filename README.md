# E-Commerce Platform - Frontend Development using FakeStore API

## **Live Demo**
[Live Application URL](https://e-commerce-shop-sphere-git-main-nayab-nakhwas-projects.vercel.app/)

## **GitHub Repository**
[GitHub Repository Link](https://github.com/nayab-nakhwa/E-Commerce-ShopSphere)

- Access to the repository is private and has been granted to `Authenticate9`.


## **Overview**
This is a responsive and user-friendly e-commerce platform built using React, integrating the FakeStore API. The application supports features like product listing, filtering, sorting, cart management, and wishlist functionality, tailored for both guest and authenticated users.

---

## **Features**
### **1. Product Viewing**
- Fetches and displays all products from the FakeStore API.
- Pagination for easy navigation through products.
- Single product details page with detailed information.

### **2. Filtering and Sorting**
- Filter products by categories.
- Sort products by price or rating.

### **3. Cart Management**
- Add/remove products to/from the cart.
- Restricts checkout functionality to authenticated users.

### **4. Wishlist Functionality**
- Authenticated users can add/remove products to/from their wishlist.

### **5. User Differentiation**
- Guest Users:
  - Can browse products and add items to the cart.
  - Cannot access checkout or wishlist.
- Authenticated Users:
  - Full access, including cart checkout and wishlist management.

### **6. Routing**
- **Public Routes:**
  - `/products`: View all products.
  - `/products/:id`: View details of a single product.
- **Private Routes:**
  - `/cart`: Access cart (for authenticated users only).
  - `/wishlist`: Manage wishlist (for authenticated users only).

---

## **Technologies Used**
- **Frontend Framework:** React (with Vite for build tooling)
- **State Management:** Context API or Redux
- **Routing:** React Router
- **Styling:** Tailwind CSS for responsive and modern design
- **API Integration:** Axios for data fetching
- **Hosting Platform:** Netlify

---

## **API Endpoints**
The application integrates with the [FakeStore API](https://fakestoreapi.com) using the following endpoints:

| Endpoint                 | Method | Description                         |
|--------------------------|--------|-------------------------------------|
| `/products`              | GET    | Fetches all products               |
| `/products/:id`          | GET    | Fetches details of a single product |
| `/products/categories`   | GET    | Fetches available product categories |

---


## **Installation and Setup**
### **Prerequisites**
- Node.js (v14+)
- npm or yarn
- A `.env` file for environment variables (if applicable)


## **Contact Info**
--Developer: Nayab Nakhwa
--Email: nayabnakhwa1@gmail.com
--GitHub: nayab-nakhwa
