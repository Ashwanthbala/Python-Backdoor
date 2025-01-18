This is a simple Python-based reverse backdoor tool designed to open a reverse shell when executed on a victim's machine. 
The listener script runs on the attacker's machine, waiting for an incoming connection and then triggering a reverse shell once the reverse backdoor is activated. 
The core concept behind this tool is socket programming.

Usage:

Execute the listener.py on the attacker's machine:

#python3 listener.py

Execute the reverse shell backdoor script on the victim's machine:

#python3 reverse_shell_backdoor.py

This project is intended for educational purposes.

Note: This tool will only work in Python3

