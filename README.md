🛒 Grocery Delivery App

A full-stack Grocery Delivery Application that allows users to browse products, add items to their cart, manage orders, and track deliveries in real-time. Built with a scalable backend and a clean, intuitive UI to provide a smooth shopping experience.

🚀 Features
User Features

User authentication & authorization (JWT)

Browse grocery categories and products

Add/remove items from cart

Place orders with address selection

Order tracking (Pending → Packed → Out for Delivery → Delivered)

View past orders & invoices

Admin Features

Manage products (CRUD)

Manage categories

View and update order statuses

Manage delivery partners

System Features

REST API architecture

Secure backend with validation & exception handling

Role-based access control

Smooth & responsive UI

🏗️ Tech Stack
Backend

Java

Spring Boot

Spring Data JPA

Hibernate

REST APIs

Database

PostgreSQL / MySQL

Frontend (optional depending on your stack)

React / HTML / CSS / JavaScript

Cloud & DevOps

AWS EC2 (deployment)

Git & GitHub version control

Postman (API testing)

📁 Project Structure (Example)
grocery-delivery-app/
│
├── backend/
│   ├── src/main/java/com/grocery/...
│   ├── src/main/resources/application.properties
│   └── pom.xml
│
├── frontend/
│   ├── public/
│   └── src/components/
│
└── README.md

🔧 API Endpoints (Sample)
User APIs
Method	Endpoint	Description
POST	/auth/register	Register new user
POST	/auth/login	Login user
GET	/products	Get all products
POST	/cart/add	Add product to cart
POST	/order/place	Place order
Admin APIs
Method	Endpoint	Description
POST	/admin/product	Add new product
PUT	/admin/order/{id}	Update order status
⚙️ Installation
1. Clone the Repository
git clone https://github.com/your-username/grocery-delivery-app.git
cd grocery-delivery-app

2. Backend Setup
cd backend
mvn clean install


Update your application.properties:

spring.datasource.url=jdbc:postgresql://localhost:5432/grocerydb
spring.datasource.username=postgres
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update


Run backend:

mvn spring-boot:run

3. Frontend Setup
cd frontend
npm install
npm start

📦 Deployment (AWS EC2)

Build Spring Boot jar

Upload to EC2 instance

Run using:

java -jar grocery-app.jar


Configure Nginx (optional)

Connect to domain

🧪 Testing

Postman collection included (optional)

Unit Tests using JUnit & Mockito (if added)

🤝 Contributions

Contributions are welcome! Feel free to submit PRs or raise issues.

📜 License

This project is released under the MIT License.
