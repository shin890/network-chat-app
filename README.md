# Chat Application - Computer Networks Project

## Course Information
- **Course:** ECE4109 - Computer Networks
- **Project Type:** Multi-threaded Client-Server Chat Application

## Project Overview
This is a simple peer-to-peer chat application demonstrating fundamental network communication concepts including socket programming, client-server architecture, and multi-threaded message handling.

## Requirements
- Python 3.x
- Basic networking knowledge (TCP/IP sockets)

## Setup Instructions

### 1. Server Setup
Execute `server.bat` to initialize and start the server:
```bash
server.bat
```

### 2. Client Setup
Execute `client.bat` to launch the client chat terminal:
```bash
client.bat
```

Multiple clients can connect to the same server and communicate in real-time.

## Configuration for Multiple Devices

To run clients on different machines/devices:
1. Open the relevant Python file (`client.py` or equivalent)
2. Locate the IP address definition section (typically at the top of the file)
3. Modify the server IP address to match your server's IP
4. Save the file and execute

**Example:**
```python
SERVER_IP = "192.168.1.100"  # Change to your server's IP
SERVER_PORT = 5000
```

## Architecture
- **Server:** Manages multiple client connections and routes messages between clients
- **Client:** Connects to the server and enables user messaging in a terminal interface
- **Protocol:** TCP sockets for reliable message delivery

## File Structure
- `server.bat` - Server launcher script
- `client.bat` - Client launcher script
- Python source files - Core application logic
