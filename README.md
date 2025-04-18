# Python Backdoor (Educational/Red-Team Use Only)
<br>
This project demonstrates a simple Python-based backdoor and listener setup designed for educational and ethical hacking practice only. It allows a server to interact with a client machine over a socket connection, enabling command execution, file upload/download, and remote shell access.
<br>
Warning: This project is intended strictly for use in controlled, legal environments such as labs or penetration testing simulations. Unauthorized use of this tool is illegal and unethical.
<br><br>

## Features
<br>
- Persistent socket-based connection<br>
- Remote shell execution<br>
- File upload and download capabilities<br>
- Change directory handling<br>
- JSON-based communication for reliability<br>
- Can be compiled to an executable using PyInstaller<br>
<br><br>

## How It Works
<br>
1. `server.py` listens on a specific IP and port for incoming connections.<br>
2. `backdoor.py` (when executed) connects to the server.<br>
3. Once connected, the server can:<br>
   - Execute commands remotely<br>
   - Upload/download files<br>
   - Navigate the target file system<br>

