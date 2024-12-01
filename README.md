
# Encrypted Chat Application

This project implements a **secure chat system** consisting of a **server** and a **client** application. It uses the **Caesar Cipher encryption** technique to transmit messages securely over a network. Both server and client applications are built using Python and feature a graphical user interface (GUI) for seamless interaction.

---

## Features

### General
- **Secure Communication**: Messages are encrypted and decrypted using Caesar Cipher with a shift value of 3.
- **Concurrent Messaging**: Allows simultaneous sending and receiving of messages using threading.
- **GUI Interface**: User-friendly graphical interface built with Tkinter.
- **Message Logs**: Displays original, encrypted, and decrypted messages.

### Server-Specific
- **Server Setup**: Host the chat server by entering an IP address and port.
- **Handles Client Connections**: Waits for a client to connect and starts secure communication.

### Client-Specific
- **Connect to Server**: Join the chat server using the provided IP address and port.
- **User Identification**: Allows users to set their username for personalized interaction.

---

## Prerequisites

- Python 3.x
- Required Python libraries:
  - `socket`
  - `threading`
  - `tkinter` (standard with Python)
  - `ttk` (for styled widgets)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/encrypted-chat-app.git
   cd encrypted-chat-app
   ```

2. Ensure Python 3.x is installed on your machine.

3. Run the **server** and **client** scripts in separate terminals.

---

## How to Use

### Server

1. Navigate to the directory containing the scripts.
2. Run the server script:
   ```bash
   python server.py
   ```
3. Enter the **IP address** and **port number** to set up the server.
4. Wait for a client to connect. Once connected, start chatting securely.

### Client

1. Navigate to the directory containing the scripts.
2. Run the client script:
   ```bash
   python client.py
   ```
3. Enter the **IP address** and **port number** of the server to connect.
4. Enter your username and start chatting securely.

---

## Folder Structure

```
encrypted-chat-app/
├── server.py          # Server-side script
├── client.py          # Client-side script
└── README.md          # Project documentation
```
---

## Notes

1. The Caesar Cipher is a basic encryption technique suitable for demonstration purposes but not for highly secure communication.
2. Ensure the server and client are on the same network or have proper port forwarding for remote connections.
3. Only one client is supported in this implementation. To support multiple clients, additional features like multi-threaded server handling would need to be implemented.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contributions

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

--- 
