# 🛠️ ServiFY

A full-stack service marketplace platform that connects customers with service providers — powered by an AI layer for smarter service discovery and recommendations.

---

## 📁 Project Structure

```
ServiFY/
├── frontend/     # Client-side app (HTML, CSS, JavaScript)
├── backend/      # REST API server (Java)
├── ai/           # AI/ML layer (Python)
└── Dockerfile    # Containerization
```

---

## ✨ Features

- Browse and discover service providers
- Book and manage services
- AI-powered recommendations and service matching
- User authentication and profiles
- Responsive, modern UI

---

## 🧰 Tech Stack

| Layer     | Technology              |
|-----------|-------------------------|
| Frontend  | HTML, CSS, JavaScript   |
| Backend   | Java (Spring Boot)      |
| AI Module | Python                  |
| DevOps    | Docker, Shell scripts   |
| Hosting   | Vercel                  |

---

## 🚀 Getting Started

### Prerequisites

- Java 17+
- Node.js (for frontend tooling)
- Python 3.9+
- Docker (optional)

---

### 1. Clone the Repository

```bash
git clone https://github.com/Jeeshan-Shrestha/ServiFY.git
cd ServiFY
```

---

### 2. Run the Backend

```bash
cd backend
./mvnw spring-boot:run
```

The backend server will start on `http://localhost:8080`.

---

### 3. Run the Frontend

```bash
cd frontend
# Open index.html in your browser, or serve it with a local server:
npx serve .
```

---

### 4. Run the AI Module

```bash
cd ai
pip install -r requirements.txt
python main.py
```

---

### 5. Run with Docker

```bash
docker build -t servify .
docker run -p 8080:8080 servify
```

---

## 📄 License

This project is open source. Feel free to fork and contribute!
