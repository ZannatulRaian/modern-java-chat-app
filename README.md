# Modern Java Multi-Client Chat Application

[![Java](https://img.shields.io/badge/Java-17-orange)](https://www.oracle.com/java/)

A **real-time, multi-client chat application** built in **Java** featuring:

- Rounded chat bubbles like modern messaging apps  
- User list panel displaying all connected users  
- Unique colors for each user  
- Two-sided real-time chat: messages appear for all clients, including the sender  
- Notifications for user join/leave  
- GUI built with **Swing**  

---

## Features

- **Two-sided Chat**: All clients see every message  
- **Rounded Chat Bubbles**: Color-coded messages per user  
- **User List Panel**: Shows online users dynamically  
- **Notifications**: Join/Leave messages  
- **Send via Enter Key or Send Button**  
- **Menu Options**: Clear Chat / Exit  
- Multi-client support with TCP sockets  

---

## Screenshots & Demo

| Feature | Screenshot / GIF |
|---------|----------------|
| Chat Window | 
<img width="979" height="608" alt="Screenshot 2025-12-18 194711" src="https://github.com/user-attachments/assets/c95c1682-db6d-44db-a036-84e494adee47" />
| Two-sided Messaging | 
<img width="977" height="612" alt="Screenshot 2025-12-18 194723" src="https://github.com/user-attachments/assets/0db73af1-998d-473f-824c-c4265101f6f7" />
| User List Panel & Option | 
<img width="981" height="608" alt="Screenshot 2025-12-18 194746" src="https://github.com/user-attachments/assets/71fd7025-02dd-413f-9f32-bc8d2314926d" />

---

## Getting Started

### Prerequisites

- **Java JDK 8 or higher**  
- **PowerShell / Terminal**  
- Optional: IDE like **VSCode**, **IntelliJ**, or **Eclipse**

### Installation

1. Clone this repository:

```bash
git clone https://github.com/ZannatulRaian/modern-java-chat-app.git
cd modern-java-chat-app
Compile Java files:

javac ChatServer.java
javac ChatClient.java
Start the server:

java ChatServer
Start clients in separate terminals:

java ChatClient
Enter unique usernames and chat!

Optional: Auto-launch with PowerShell
powershell
.\runChatApp.ps1
This script launches the server and multiple clients automatically.

How It Works
Server: Accepts connections, broadcasts messages, updates user list

Client: Connects to server, sends messages, receives broadcasts

GUI: Displays messages as colored, rounded bubbles; updates user list dynamically

Color Mapping: Each user has a unique color for easy identification

Tech Stack
Language: Java

Networking: TCP sockets

GUI: Swing

Threading: Multi-threaded client handling

Future Improvements
Private messaging between users

File sharing in chat

Persistent message history

Customizable themes

Emoji support

Message encryption

License
This project is licensed under the MIT License.
