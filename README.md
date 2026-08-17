# 🔄 ReElectro – Electronic Thrift Store

A multi-vendor e-commerce platform for buying and selling **used and pre-owned electronic devices**.

## 📌 About the Project

**ReElectro** is a full-stack marketplace developed using the **MERN stack** that connects buyers and sellers of second-hand electronics. Sellers can create and manage listings for their used devices, while buyers can explore products, view their details, and place orders through the platform.

The project was developed as a **college project** to gain practical experience in building a real-world e-commerce application with multiple users, product management, authentication, orders, and payment functionality.

## ✨ Key Features

### 🔐 User Authentication

* User registration and login
* Secure authentication
* User account management
* Support for both buyers and sellers
* Different functionality based on user roles

### 🛒 Electronics Marketplace

* Explore pre-owned electronic products
* View complete product details
* Display product specifications and descriptions
* Sellers can upload their own listings
* Product reviews and ratings

### 🏬 Multi-Seller Marketplace

ReElectro allows different users to become sellers and offer their used electronic devices on the platform.

**Sellers can:**

* Add new electronic products
* Provide product descriptions and specifications
* Upload product information
* Manage their own listings
* Handle incoming orders

**Buyers can:**

* Search and browse available products
* Check product and seller information
* View product details
* Add products to their purchase flow
* Place orders

### 💰 Checkout & Payment

The application provides an e-commerce checkout process with supported payment methods such as:

* Cash on Delivery
* Online payment

> Modify this section according to the payment methods actually implemented in the project.

### 📋 Order Handling

* Create and place product orders
* Store order information
* Manage order status
* View order-related details

> Update this section if additional order-tracking features are implemented.

## 🧰 Technologies Used

### Frontend

* React.js
* JavaScript
* HTML
* CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Supporting Technologies

* RESTful APIs
* Authentication
* Payment integration
* Git & GitHub

> Add any additional libraries or services used in the actual implementation.

## 🏗️ Application Architecture

```text
                         ReElectro
                            │
                ┌───────────┴───────────┐
                │                       │
             React.js              Node.js
             Frontend               Backend
                │                       │
                │                  Express.js
                │                       │
                └───────────┬───────────┘
                            │
                         MongoDB
                            │
             ┌──────────────┼──────────────┐
             │              │              │
           Users         Products        Orders
```

## 🔄 Platform Workflow

### 👤 Buyer Flow

```text
Register / Login
       ↓
Explore Products
       ↓
Select a Device
       ↓
View Product Information
       ↓
Proceed to Checkout
       ↓
Select Payment Method
       ↓
Confirm Order
       ↓
View Order Details
```

### 🏪 Seller Flow

```text
Register / Login
       ↓
Access Seller Features
       ↓
Add Electronic Device
       ↓
Enter Product Information
       ↓
Publish Listing
       ↓
Receive Customer Orders
       ↓
Manage Orders
```

## 🚀 Installation & Setup

### Requirements

Before running the project, install:

* Node.js
* npm
* MongoDB

### Clone the Project

```bash
git clone https://github.com/kriti0317/ThriftStore-MernStack-Project.git
```

Move into the project directory:

```bash
cd ThriftStore-MernStack-Project
```

### Install Packages

Install the required dependencies:

```bash
npm install
```

If the application contains separate frontend and backend folders, install the dependencies inside each directory as required.

### ⚙️ Environment Configuration

Create a `.env` file and provide the required configuration values.

Example:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PAYMENT_GATEWAY_KEY=your_payment_gateway_key
```

**Important:** Do not upload `.env` files containing passwords, API keys, database credentials, or other private information to GitHub.

### ▶️ Run the Project

If the project is configured with a development script:

```bash
npm run dev
```

Depending on the project structure, you may also need to run the frontend and backend separately:

```bash
npm run client
```

```bash
npm run server
```

> Use the commands defined in the project's `package.json`.

## 🤝 Contribution

Suggestions and improvements are welcome.

To contribute:

1. Fork the repository.
2. Create a separate branch for your changes.
3. Implement your changes.
4. Commit the updates.
5. Push the branch to GitHub.
6. Submit a pull request.

**ReElectro** was developed as a college project using the **MERN stack**.

### Team Members

* Rushal Manandhar
* Xenium Suwal
* Malika Budhathoki
* Kriti Koju

---

⭐ If you find **ReElectro** useful or interesting, consider giving the repository a star!
