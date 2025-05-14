# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![Screenshot 2025-05-14 210541](https://github.com/user-attachments/assets/79657b50-cb5a-4341-9424-091e0258d77c)

## OUPUT - ARP
![Screenshot 2025-05-14 210558](https://github.com/user-attachments/assets/adaf96c6-ff9f-4983-8825-c690e0cb3224)

## PROGRAM - RARP
![Screenshot 2025-05-14 210621](https://github.com/user-attachments/assets/3df49bba-b6b7-441a-9ecc-c192428b877a)

## OUPUT -RARP
![Screenshot 2025-05-14 211113](https://github.com/user-attachments/assets/b951d3cf-948e-4417-8072-34d05a5c165e)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
