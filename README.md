# Chat Application in Java

## Overview
This is a simple chat application built using Java Swing and Java Socket Programming. The application consists of two components: a **server** and a **client**. The server listens for incoming messages from the client, and the client can send messages to the server, allowing for real-time communication.

## Features
- **Java Swing**: The desktop user interface is created using JFrame and Panels for layout management.
- **Socket Programming**: Utilizes sockets for communication between the server and client. The server sends messages to the client, and the client can send messages to the server as well.
- **ActionListener**: Used on buttons such as 'Send' to trigger the action of sending messages, and 'Back' to close the application.
- **Real-time Messaging**: Messages are exchanged between the client and server in real-time.
- **User Interface**: Simple yet functional interface with labels, buttons, and text fields for a seamless chat experience.

## Technologies Used
- **Java Swing**: For creating the graphical user interface (GUI).
- **Java Socket Programming (TCP)**: For client-server communication.
- **ActionListener**: For handling events like button clicks.
- **JPanel and JFrame**: For organizing and displaying components in the GUI.

## How It Works
1. **Server**: The server listens for incoming connections from clients on a specific port.
2. **Client**: The client connects to the server using the server's IP address and port number.
3. **Message Exchange**: Messages can be sent back and forth between the server and client using a text input field and the 'Send' button.
4. **Close the Application**: The 'Back' button allows the user to close the application.

## Getting Started

### Prerequisites
- Java Development Kit (JDK) installed on your system.
- A text editor or an IDE (like IntelliJ IDEA or Eclipse) for writing Java code.

### Steps to Run
1. Clone the repository:

   ```bash
   git clone https://github.com/kanojiaritika/ChatApplication.git
