🛒 Grocery Tracker – Backend (Spring Boot)

This is the backend part of the Grocery Tracker CRUD Application, developed using Spring Boot.
It provides REST APIs to perform CRUD operations on grocery items and communicates with the frontend using JSON over HTTP.

The backend is Dockerized and deployed on Render ☁️.

🚀 Technologies Used

Java 17

Spring Boot 3.2.x

Spring Data JPA

H2 Database

Maven

Docker

Render (Cloud Deployment)

✨ Features

Create grocery items

Read all grocery items

Update grocery items

Delete grocery items

RESTful API architecture

Docker containerization

Cloud deployment using Render

📌 API Endpoints
Method	Endpoint	Description
POST	/api/groceries	Add new grocery item
GET	/api/groceries	Get all grocery items
PUT	/api/groceries/{id}	Update grocery item
DELETE	/api/groceries/{id}	Delete grocery item
▶️ How to Run Backend (Local)
1️⃣ Clone the repository
git clone https://github.com/3BCA23SUCA32/grocery_tracker_backend.git
cd grocery_tracker_backend

2️⃣ Open in IntelliJ IDEA

Open the project

Make sure Java 17 is selected

Maven dependencies will auto-download

3️⃣ Run the application

Run:

GroceryApplication.java
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/3887c4c2-50b0-46cd-9c41-d2db9b6d3533" />


4️⃣ Backend will start at
http://localhost:8080

🐳 Run Backend Using Docker
1️⃣ Build Docker image
docker build -t grocery-tracker-backend .

2️⃣ Run Docker container
docker run -p 8080:8080 grocery-tracker-backend
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/d1e91f8c-5620-4fe7-a76d-4e710ff667fb" />


3️⃣ Backend URL
http://localhost:8080/api/groceries

🌐 Deployed Backend (Render)

Production URL:

https://<your-render-backend-url>/api/groceries


The backend is deployed using:

Docker

Render Web Service

Automatic build & deployment from GitHub

🗄 Database

H2 In-Memory Database

Auto-configured by Spring Boot

No external database required

SONARQUBE:
![WhatsApp Image 2026-02-07 at 4 57 03 PM (1)](https://github.com/user-attachments/assets/46e5c448-d851-4333-99cd-62fa74fb2290)



📂 Project Structure
src/main/java/com/example/grocerytracker/
├── controller/
├── service/
├── repository/
├── model/
└── GroceryApplication.java
![WhatsApp Image 2026-02-07 at 4 57 03 PM (2)](https://github.com/user-attachments/assets/edc8a771-820d-4f99-9edc-24f0d20434d4)

🧠 Learning Outcome

Spring Boot REST API development

CRUD operations using Spring Data JPA

Docker containerization

Cloud deployment using Render

Frontend–backend integration

👩‍💻 Developed By

Varsha Dhanvarsha B
Grocery Tracker – Full Stack Project
