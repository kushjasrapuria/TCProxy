# TCProxy
A TCP proxy for monitoring data being sent and received over TCP Protocol

Can be further modified to modify data being sent or being received

# Modifications for modifying data
Line 47:

Modify function request_handler for any modifications in requests

Line 51:

Modify function response_handler for any modifications in responses

# Usage
python3 ./tcproxy.py [localhost] [localport] [remotehost] [remoteport] [receive_first]

# Example
python3 ./tcproxy.py 127.0.0.1 9000 10.12.132.1 9000 True
