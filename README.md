# FarmConnectWebApp
FarmConnect aims to empower local farmers by providing a digital marketplace to sell their products directly to consumers. This full-stack mobile application bridges the gap between rural producers and urban buyers, enabling seamless product listings, purchases, reviews, income tracking, and donation support — all in one unified platform.
# 🌾 FarmConnect – Empowering Farmers Through Digital Commerce

FarmConnect is a full-stack agri-commerce mobile application that connects farmers directly with consumers. It enables farmers to showcase their products, receive reviews, track income, and request donations, while consumers can browse, purchase, and support farmers – all from a single platform.

## 🎯 Objective

FarmConnect aims to empower local farmers by providing a digital marketplace to sell their products directly to consumers. This app bridges the gap between rural producers and urban buyers, promoting transparency, fair pricing, and community-driven support.

---

## 🚀 Features

### 👨‍🌾 Farmer Side
- ✅ Secure login (predefined credentials)
- 🛒 Add products (with category, name, details, and price)
- 🌟 View consumer reviews and ratings
- 💰 Track income from sales (date-wise)
- 🙏 Create donation requests with image & description

### 🧑‍💼 Consumer Side
- 🥬 Browse vegetables & fruits uploaded by farmers
- 📦 Add to cart and purchase using Razorpay integration
- ✍️ Give reviews and ratings to purchased products
- 🤝 View and donate to farmer’s donation requests

---

## 🛠️ Tech Stack

### 💻 Frontend
- **React Native** with **TypeScript**
- **React Native Paper** for UI
- **Zustand** for state management
- **Expo Router** for navigation
- **AsyncStorage** for session & cart persistence

### 🌐 Backend
- **Node.js** with **Express** and **TypeScript**
- **MongoDB** (via Mongoose)
- **JWT** for authentication
- **Bcrypt** for password hashing
- **Razorpay** for payment gateway

---

## 🔐 Predefined Farmer Login Credentials
| Email                | Password       |
|---------------------|----------------|
| santosh@gmail.com   | Santosh@123    |
| manjusha@gmail.com  | Manjusha@123   |
| trilok@gmail.com    | Trilok@123     |
| abhi@gmail.com      | Abhi@123       |

---

## 📖 Research Publication

This project is officially published in:

**IJSRA (International Journal of Science and Research Archive)**  
*“FarmConnect: Bridging Farmers and Consumers Through a Full-Stack Agri-Commerce Platform”*  
https://journalijsra.com/sites/default/files/fulltext_pdf/IJSRA-2025-1112.pdf

---

## 📸 Screenshots

Kindly please check the screenshots in my journal attached link https://journalijsra.com/sites/default/files/fulltext_pdf/IJSRA-2025-1112.pdf

## ⚙️ Setup Instructions

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/farmconnect.git

   
**2.  Install dependencies:**

```bash
cd farmconnect
npm install
Set environment variables (Razorpay keys, Mongo URI, etc.)

3. **Run the app:**

```bash

expo start
