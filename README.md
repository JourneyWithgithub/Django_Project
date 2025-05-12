Inventory Management System
This project is a Django-based Inventory Management System designed to manage buyers, suppliers, and products efficiently across multiple services. It uses Django REST Framework (DRF) for building RESTful APIs and supports secure token-based authentication for API access.

🔧 Features
🔐 Token Authentication for secure API communication

👤 Buyers and Suppliers Management with full CRUD functionality

📦 Product Management integrated from a separate microservice

🖥️ Admin Dashboard showing real-time counts of buyers, suppliers, and products

💬 User Feedback with Django Messages Framework for status updates

🔄 Modular Microservices Architecture using separate Django apps on different ports

📡 API Endpoints
/api/buyers/ – List & Create Buyers

/api/buyers/<id>/ – Retrieve, Update, Delete a Buyer

Token authentication available at /api-token-auth/

💡 Technologies Used
Django 4.x

Django REST Framework

Requests (for cross-service communication)

Bootstrap (for basic UI styling)

🚀 Getting Started
To run the project locally:

bash
Copy
Edit
git clone https://github.com/your-username/inventory-management-system.git
cd inventory-management-system
pip install -r requirements.txt
python manage.py runserver
