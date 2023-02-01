Don't forget to add vid directory(frames) to your working code directory.

Compile client.cpp:

g++ -o Client Client.cpp -O2 -L/usr/X11R6/lib -lm -lpthread -lX11

Execute client code:

./Client IP PortNum --> where IP: One of your ip addresses, PortNum: Server Port Number for RTP udp socket

Compile server.cpp:

g++ Server.cpp -o Server -pthread

Execute server code:

./server PortNum --> where PortNum: Server Port Number for RTP udp socket

**RTSP client+server code is commented in the .cpp files because it is not complete.
