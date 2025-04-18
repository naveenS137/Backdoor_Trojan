# Python Backdoor (Educational/Red-Team Use Only)
<br>
This project demonstrates a simple Python-based backdoor and listener setup designed for educational and ethical hacking practice only. It allows a server to interact with a client machine over a socket connection, enabling command execution, file upload/download, and remote shell access.
<br>
Warning: This project is intended strictly for use in controlled, legal environments such as labs or penetration testing simulations. Unauthorized use of this tool is illegal and unethical.
<br><br>>
## Features
<br>
- Persistent socket-based connection
- Remote shell execution
- File upload and download capabilities
- Change directory handling
- JSON-based communication for reliability
- Can be compiled to an executable using PyInstaller
<br><br>

## How It Works
<br>
1. `server.py` listens on a specific IP and port for incoming connections.
2. `backdoor.py` (when executed) connects to the server.
3. Once connected, the server can:
   - Execute commands remotely
   - Upload/download files
   - Navigate the target file system

