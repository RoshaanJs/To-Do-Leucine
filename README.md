# *📌 Task Management Application*  
A *simple Task Management Application* built using *Spring Boot, PostgreSQL, Docker, and deployed on Render. This application allows users to **add, update, view, and delete tasks* with a minimal frontend.

---

## *🚀 Live Demo*  
🔗 *[Click here to access the deployed app](https://task-management-tbz6.onrender.com)*  

---

## *📌 Features*  
✅ Add New Tasks  
✅ View All Tasks  
✅ Update Task Details  
✅ Delete Tasks  
✅ Status Tracking (Completed/Pending)  

---

## *🛠 Tech Stack*  
- *Backend:* Spring Boot (Java), Spring Data JPA  
- *Frontend:* HTML, CSS, JavaScript  
- *Database:* PostgreSQL (Previously MySQL, now switched to PostgreSQL)  
- *Deployment:* Docker & Render  

---

## *📂 Project Structure*  

├── src/main/java/com/example/demo
│   ├── controller/TaskController.java  # REST API Endpoints
│   ├── service/TaskService.java        # Business Logic
│   ├── repository/TaskRepository.java  # Database Access Layer
│   ├── model/Task.java                 # Task Entity Model
│   ├── TodoAppApplication.java         # Main Spring Boot Entry
│
├── src/main/resources
│   ├── static/index.html  # Frontend UI
│   ├── static/styles.css  # CSS Styles
│   ├── static/script.js   # JavaScript for API Calls
│   ├── application.properties  # Database Configuration
│
├── Dockerfile              # Docker Image Configuration
├── docker-compose.yml      # Multi-container Setup (App + PostgreSQL)
├── pom.xml                 # Maven Dependencies
├── README.md               # Documentation


---

## *🔧 Setup & Run Locally*
### *⿡ Clone the Repository*
sh
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME


### *⿢ Run with Docker*
sh
docker-compose up --build -d

- This will start the *Spring Boot app* and *PostgreSQL database* together.

### *⿣ Access the App*
- Open *http://localhost:8080* in your browser.

---

## *📡 API Endpoints*
| Method | Endpoint        | Description       |
|--------|---------------|------------------|
| GET    | /tasks       | Get all tasks   |
| POST   | /tasks       | Add new task    |
| PUT    | /tasks/{id}  | Update task     |
| DELETE | /tasks/{id}  | Delete task     |

---

## *🌍 Deployment on Render*
This project is deployed on Render using *Docker & PostgreSQL*.  

### *Steps to Deploy on Render:*
⿡ Push your *Dockerized* project to GitHub.  
⿢ Connect GitHub repo to Render.  
⿣ Deploy using *Dockerfile & docker-compose.yml*.  
⿤ Add *PostgreSQL Database* via Render.  
⿥ Set *Environment Variables* (Database URL, User, Password).  

---

## *💡 Future Improvements*
- Add *User Authentication*  
- Implement *Task Filtering & Sorting*  
- UI Enhancements  

---

### *📜 License*  
This project is *open-source* under the *MIT License*.

---

### *🧑‍💻 Author*
👤 *Roshaan Js*  
🔗 GitHub: [RoshaanJs](https://github.com/RoshaanJs)  
