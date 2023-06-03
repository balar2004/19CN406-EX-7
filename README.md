# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND
# AIM:
To write the python program for simulating Traceroute command
# ALGORITHM:
1. Start the program.
2. Get the frame size from the user.
3. To create the frame based on the user request.
4. To send frames to server from the client side.
5. If your frames reach the server, it will send ACK signal to client
otherwise it will sendNACK signal to client.
6. Stop the program
# PROGRAM:
```
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
# OUTPUT:
![Output 4 2](https://github.com/balar2004/19CN406-EX-7/assets/118791778/0a2d6b2a-fb02-4d08-983b-cff304e2be4f)
# RESULT:
Thus, the python program for simulating Traceroute command was successfully executed.
