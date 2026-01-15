🛒 CliqtoKart

A lightning-fast quick commerce platform inspired by modern instant-delivery apps

CliqtoKart is a full-stack quick commerce application designed to deliver daily essentials at blazing speed.
Built with a scalable backend, AI-powered intelligence, and a modern frontend, it focuses on performance, reliability, and smart user interactions.

🚀 Features

⚡ Ultra-fast product discovery & ordering

🤖 AI-powered assistant for search, recommendations & FAQs (LangChain)

🧠 Smart intent-based queries instead of rigid filters

📦 Real-time inventory management

🧾 Order tracking & status updates

🔐 Secure authentication & role-based access

🛠 Modular, scalable backend architecture

🧑‍💻 Tech Stack
Backend

FastAPI – High-performance REST APIs

Django – Admin panel & core services

PostgreSQL – Relational database

LangChain – AI workflows & conversational logic

Frontend

JavaScript (Vanilla / Framework-based) – Dynamic & responsive UI

AI / Intelligence

Natural language product search

Conversational shopping assistant

Context-aware recommendations

🏗 Architecture Overview
Frontend (JS)
     |
FastAPI (API Gateway)
     |
--------------------------------
|           |                  |
LangChain   Django Services   Auth
|           |
AI Logic    PostgreSQL


FastAPI handles all high-speed API communication

Django manages admin tasks, inventory, and internal workflows

LangChain powers AI-based interactions

PostgreSQL stores users, products, orders, and logs

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/cliqtokart.git
cd cliqtokart

2️⃣ Backend Setup
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

3️⃣ Database Setup
psql -U postgres
CREATE DATABASE cliqtokart;


Update database credentials in .env.

4️⃣ Run Services
# Django
python manage.py migrate
python manage.py runserver

# FastAPI
uvicorn main:app --reload

5️⃣ Frontend
cd frontend
npm install
npm start

🤖 AI Capabilities (LangChain)

Conversational product search

Context-aware recommendations

Intelligent FAQs & order assistance

Dynamic query routing to backend services

🔐 Security

JWT-based authentication

Role-based access (Admin / User / Delivery)

Secure API validation

Environment-based secrets management

📈 Scalability & Performance

Async APIs using FastAPI

Optimized PostgreSQL queries

Modular microservice-friendly design

Easy cloud deployment readiness

🧪 Future Enhancements

🚴 Live delivery partner tracking

📍 Location-based inventory optimization

💳 Payment gateway integration

📊 Analytics dashboard

🧠 Personalized AI shopping agent

👨‍👩‍👧 Team

Built with ❤️ during a hackathon by Team CliqtoKart
Focused on speed, intelligence, and real-world scalability.

