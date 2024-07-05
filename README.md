# Group Messaging Application

## Overview
This application provides a real-time group messaging service using ZeroMQ (ZMQ). It consists of three main components: a Group Messaging Server, a Message App Server, and a Message App User interface. The system allows users to join groups, send and receive messages, and manage group memberships.

## Dependencies
- ZeroMQ (ZMQ)
- Python's `threading`, `datetime`, `json`, `uuid`, `socket` modules
- Additional scripts: `port.py`, `test.py`

## Installation
1. Ensure Python 3.x is installed on your system.
2. Install ZeroMQ: `pip install zmq`
3. Clone the repository or download the source code.
4. Install other dependencies as needed.

## Usage

### Group Messaging Server
- Manages real-time communication within groups.
- Run the server: `python group_messaging_server.py`
- Follow the prompts to set up a group.

### Message App Server
- Handles group registration and lists active groups.
- Start the server: `python message_app_server.py`
- The server will listen for incoming requests automatically.

### Message App User
- User interface for interacting with the messaging system.
- Run the script: `python message_app_user.py`
- Follow the on-screen prompts to join groups, send messages, etc.

## Key Features
- **Real-time Messaging:** Send and receive messages instantly within groups.
- **Group Management:** Join or leave groups as desired.
- **Message History:** Retrieve past messages from group chats.
- **Concurrent Access:** Supports multiple users interacting simultaneously.
- **Error Handling:** Gracefully manages errors and exceptions.

## Note
This application is designed for educational and demonstration purposes. It showcases the use of ZeroMQ for building real-time messaging systems with Python.
