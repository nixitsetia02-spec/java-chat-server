# Java Chat Server

A desktop-based chat application developed using **Java Socket Programming** and **MySQL**. The application provides user authentication through a MySQL database and enables real-time communication between connected users over a local network.

---

## Features

- User Login Authentication
- MySQL Database Integration
- Real-time Client-Server Communication
- Java Socket Programming
- Multi-user Chat Support
- Online User List
- Graphical User Interface (Java AWT/Swing)
- Secure Login using Prepared Statements

---

## Technologies Used

- Java
- Java AWT/Swing
- Java Socket Programming
- MySQL
- JDBC (MySQL Connector/J)

---

## Project Structure

```
Chat-Server/
│
├── ChatClient.java
├── Login.java
├── Login.bat
├── mysql-connector-j-9.7.0/
├── README.md
└── ...
```

---

## Requirements

- Java JDK 17 or later
- MySQL Server
- MySQL Connector/J
- Any Java IDE (NetBeans, IntelliJ IDEA, Eclipse, VS Code)

---

# How to Run

## Step 1: Set Up the Database

1. Create a MySQL database named:

```
dbchat
```

2. Create the required login table.

3. Insert user credentials into the table.

4. Update the database username and password in `Login.java` if necessary.

---

## Step 2: Start the Chat Server

Compile and run the server application.

Ensure the server is running before starting any clients.

---

## Step 3: Start the Client

Run:

```
Login.java
```

> **Application Entry Point:** `Login.java`

Enter your username and password.

After successful authentication, the chat window will open automatically.

---

## Functionalities

- User Authentication
- Client-Server Communication
- Real-time Messaging
- Online User Display
- Graphical Chat Window
- Local Network Communication

---

## Platform Support

- Windows
- Linux
- macOS (with Java installed)

---

## Future Enhancements

- User Registration
- Group Chat
- File Sharing
- Image Sharing
- Emoji Support
- Message History
- Encryption
- Private Messaging
- Online/Offline Status
- Voice and Video Calling

---

## Developer

**Nixit Setia**

B.E. Computer Engineering (COE)

Thapar Institute of Engineering and Technology

---

## License

This project is licensed under the **MIT License**.

---

## Acknowledgements

This project was developed to strengthen concepts of:

- Java Programming
- Socket Programming
- Networking
- Multithreading
- JDBC
- MySQL Database Connectivity
- Client-Server Architecture
