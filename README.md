# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- # Real-time Chat Application

## Overview
This is a **real-time chat application** built using **Java Spring Boot WebSocket** for real-time communication between clients and the server. The application allows users to create chat rooms and invite participants to engage in real-time conversations.

## Technologies Used
- **Java Spring Boot** – Backend framework
- **WebSocket** – Real-time communication between client and server
- **Docker** – Containerization and deployment

## Features
- Users can **create chat rooms**.
- Users can **invite participants** to join chat rooms.
- **Real-time chat messaging** via WebSocket between the client and server.
- **Docker containerization** for easy deployment and scalability.

## Setup & Installation

### Prerequisites
Ensure you have the following installed on your system:
- **Java 17+**
- **Maven**
- **Docker**

### Steps to Run the Application

1. **Clone the repository:**
   
   - git clone https://github.com/kundusomnath610/front-chat.git
     
2. **Run the application:**
   ```sh
   npm run dev
   ```
3. **Run the application using Docker:**
   ```sh
   docker build -t chat-application .
   docker run -p 8080:8080 chat-application
   ```

## WebSocket Endpoint

The application uses WebSocket for real-time communication. Connect using:


## API Endpoints

| Endpoint         | Method | Description |
|-----------------|--------|-------------|
| `/create-room`  | POST   | Create a new chat room |
| `/join-room`    | POST   | Join an existing chat room |
| `/send-message` | POST   | Send a message to a room |

## Contributing
Contributions are welcome! Feel free to open issues and submit pull requests.

Screenshot Of project:-

![Landing Page](https://github.com/user-attachments/assets/b92a03e4-7134-451f-9b6b-708b8ffdcf9a)

![Chating with group](https://github.com/user-attachments/assets/43aa46be-6ae9-4883-bb57-bfc42c7495e0)
