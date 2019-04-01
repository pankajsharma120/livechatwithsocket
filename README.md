# livechatwithsocket
This is simple django based web application based on channel sockets for live chat in group for public. You can modiy `connect` in consumers.py and put rules before `accept` to make this application more specific.

# Dependencies

Redis server - Download and install redis server - https://redis.io/download
django channels - pip install -U channels
channel redis - pip install channels_redis

# Use
Go to - `127.0.0.1:8000/chat/` 

Input chat room name and enter in room. Enter the same room name in different devices and start chatting.
