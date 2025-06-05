# java-chat-application

Company - Codtech IT Solutions
Name - Manav Pathrol
Inter Id - CT04DL1071
Domain - Java Programming
Duration - 4 Weeks
Mentor -  Mr. Muzammil Ahmed


# 💬 Java Multi-Client Chat Application Using Sockets and Threads

## 📌 Project Overview

This project is a **real-time chat application** built using **Java Sockets** and **Multithreading**, allowing multiple clients to connect and communicate with a single server concurrently. Designed as a foundational networking project for students and beginners, it showcases the core concepts of socket programming, input/output stream handling, and concurrency through threading.

The server listens for incoming connections, and each connected client is assigned its own thread to maintain parallel conversations. This system is scalable for basic text-based messaging, similar to early chatroom systems, and provides the foundation for more advanced messaging platforms.

---

## 🚀 Features

* 🌐 Server program that handles multiple client connections
* 📱 Client program with real-time message sending and receiving
* 🧵 Uses Java multithreading to manage each client on a separate thread
* 📡 Communication happens over TCP sockets
* 📥 Console-based user interface for simplicity
* 🔄 Continuous message broadcast to all active clients

---

## ⚙️ Technologies Used

* Java SE 8 or higher
* `java.net.Socket` and `java.net.ServerSocket`
* `java.io.BufferedReader`, `PrintWriter`, `InputStreamReader`
* `java.lang.Thread` for concurrent handling

---

## 🗂️ File Structure

```
ChatApp/
├── Server.java         # Main server logic - accepts connections and relays messages
├── Client.java         # Client logic - connects to server and handles I/O
├── README.md
└── .gitignore
```

---

## ▶️ How to Run

### 1. Compile the Files

```bash
javac Server.java
javac Client.java
```

### 2. Run the Server

```bash
java Server
```

You will see:

```
Server is running...
Waiting for clients to connect...
```

### 3. Run Clients (in separate terminals)

```bash
java Client
```

Each client will be prompted for a username and can begin chatting.

---

## 🧪 Sample Output

### Client A:

```
Enter your name: Alice
[Alice]: Hello everyone!
[Bob]: Hi Alice!
```

### Client B:

```
Enter your name: Bob
[Alice]: Hello everyone!
[Bob]: Hi Alice!
```

The server broadcasts each message to all connected clients in real time.

---

## 🎯 Learning Objectives

* Understand the basics of **socket programming** in Java
* Grasp the role of **input/output streams** in network communication
* Learn how to use **threads** to handle multiple simultaneous client sessions
* Design a simple **client-server architecture**
* Explore the concept of **message broadcasting** to connected clients





