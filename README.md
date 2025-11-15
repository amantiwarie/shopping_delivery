# 🛒 Grocery Delivery App

A full-stack Grocery Delivery Application that enables users to browse products, manage carts, place orders, and track delivery status. Built with a scalable backend architecture and clean UI for a seamless grocery shopping experience.

---

## 🚀 Features

### User Features
- User registration & login (JWT)
- Browse grocery products & categories
- Add/remove items from cart
- Place orders with address support
- Order status tracking (Pending → Packed → Out for Delivery → Delivered)
- View previous orders

### Admin Features
- Manage products (Add/Update/Delete)
- Manage categories
- Update order status
- Manage delivery personnel

### System Features
- REST API based backend
- Role-Based Access Control (User/Admin)
- Input validation & global exception handling
- Scalable layered architecture

---

## 🏗️ Tech Stack

### Backend
- Java  
- Spring Boot  
- Hibernate  
- Spring Data JPA  
- REST APIs  

### Database
- PostgreSQL / MySQL  

### Cloud / Deployment
- AWS EC2  

### Tools
- Git  
- GitHub  
- Postman  

---

## 📁 Project Structure (Example)

grocery-delivery-app/
│
├── backend/
│ ├── src/main/java/com/grocery/...
│ ├── src/main/resources/application.properties
│ └── pom.xml
│
├── frontend/
│ ├── public/
│ └── src/components/
│
└── README.md



---

## 🔧 API Endpoints (Sample)

### User APIs
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | /auth/register | Register user |
| POST   | /auth/login    | Login user |
| GET    | /products      | List all products |
| POST   | /cart/add      | Add to cart |
| POST   | /order/place   | Place order |

### Admin APIs
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | /admin/product     | Add product |
| PUT    | /admin/product/{id}| Update product |
| PUT    | /admin/order/{id}  | Update order status |

---

## ⚙️ Installation

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/grocery-delivery-app.git
cd grocery-delivery-app


