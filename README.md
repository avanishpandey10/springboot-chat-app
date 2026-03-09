# 💬 Spring Boot Real-Time Chat Application

A simple **Real-Time Chat Application** built using **Spring Boot, WebSockets, STOMP, and SockJS**.  
This project demonstrates how real-time messaging works between multiple users without refreshing the page.

---

## 🚀 Features

- Real-time messaging
- Multiple users can join chat
- WebSocket communication
- STOMP messaging protocol
- SockJS fallback support
- Simple and responsive UI
- Messages update instantly

---

## 🛠️ Tech Stack

**Backend**
- Java
- Spring Boot
- Spring WebSocket
- STOMP Protocol
- SockJS

**Frontend**
- HTML
- CSS
- JavaScript
- Bootstrap

**Build Tool**
- Maven

---

## 📂 Project Structure

```
springboot-chat-app
│
├── src/main/java/com/chat/demo
│   ├── AppApplication.java
│   ├── controller
│   ├── model
│   └── config
│
├── src/main/resources
│   ├── static
│   │   └── chat.html
│   └── application.properties
│
└── pom.xml
```

---

## ⚙️ Installation & Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/springboot-chat-app.git
```

### 2️⃣ Open the project

Open the folder in **VS Code or IntelliJ IDEA**

### 3️⃣ Run the application

```bash
mvn spring-boot:run
```

### 4️⃣ Open in browser

```
http://localhost:8080/chat
```

---

## 📸 Application Screenshot

![WhatsApp Image 2026-03-08 at 5 49 55 PM](https://github.com/user-attachments/assets/3032490a-c2bf-4b5e-9227-f46b7e6287fd)

---

## 📖 How It Works

1. Client connects to the server using **WebSocket**
2. Messages are sent using **STOMP protocol**
3. Spring Boot broadcasts the message to all connected users
4. UI updates instantly without page refresh

---

## 🎯 Learning Outcomes

- Understanding WebSocket communication
- Implementing real-time applications
- Using STOMP messaging with Spring Boot
- Building event-driven backend systems

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork this repository and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Avanish Pandey**

GitHub:  
https://github.com/avanishpandey10

LinkedIn:  
https://www.linkedin.com/in/avanish-pandey-976b76253/

---
