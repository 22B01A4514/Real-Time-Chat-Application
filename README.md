# 💬 Real-Time Chat Application

This is a simple real-time chat application built using **Spring Boot**, **WebSocket**, **STOMP**, **SockJS**, and **Thymeleaf**. It demonstrates how to enable real-time two-way communication between clients using WebSocket and a message broker.

---

## 🚀 Features

- Real-time bi-directional messaging
- STOMP over WebSocket
- SockJS fallback support
- Simple message broker broadcasting
- Frontend built using Thymeleaf and Bootstrap

---

## 🧰 Tech Stack

| Layer        | Technology                          |
|-------------|--------------------------------------|
| Backend      | Spring Boot, Spring WebSocket, STOMP |
| Frontend     | HTML, Thymeleaf, Bootstrap, SockJS, STOMP.js |
| Message Broker | In-memory (SimpleBroker)             |

---

## 📁 Project Structure
```
chatApplication/
├── src/
│ ├── main/
│ │ ├── java/com/haritha/demo/chatApplication/
│ │ │ ├── ChatApplication.java
│ │ │ ├── config/WebSocketConfig.java
│ │ │ ├── controller/ChatController.java
│ │ │ ├── message/ChatMessage.java
│ ├── resources/
│ │ ├── templates/chat.html
│ │ └── application.properties
 ```
