# Checking listening ports and services

## What a port is
- a virtual, software-based endpoint for network communication 
- directs incoming network traffic to the correct application or service running on the system

## Why services listen on ports
- services listen on ports because ports act as sepcific communication endpoints for network traffic

## Why port 80 matters for webservers
- provides a means for transmitting web data between web servers and clients

## What command shows listening services
- ss -tuln or ss -tulpn

### -t
- Show TCP connections

### -u
- Show UDP connections

### -l

- Show only LISTENING sockets (not active outgoing connections)

### -n

- Show numeric values
- don’t resolve DNS names
- don’t translate service names like http
- faster + clearer for troubleshooting

### -p

- Show the process using the socket
- shows program name
- shows PID
- shows executable
