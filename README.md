# DiSUcord - Simple Message Networking via Channels
Welcome to DiSUcord, a simple message networking application developed as a course project for CS 408 - Computer Networks in Fall 2023. DiSUcord aims to provide a user-friendly messaging experience through channels, allowing users to communicate with others in real-time.

#### Features
DiSUcord offers a range of features to enhance your messaging experience:

#### User-Friendly Interface
Client GUI: Our intuitive graphical user interface (GUI) is designed for ease of use. With separate components for each channel, you can effortlessly navigate and interact with the application. Clear channel subscription statuses keep you informed at all times.

#### Server GUI: The server GUI acts as a monitoring tool, displaying all server-client interactions for administrative purposes. You can keep track of client connections, message transfers, and more in real-time.

#### Multiple Channels
Channel Subscriptions: DiSUcord provides two fixed channels, "IF 100" and "SPS 101." You can easily subscribe or unsubscribe from these channels through the client GUI, giving you control over your messaging preferences.

#### Message Display
Each channel features a rich text box for displaying messages sent to that specific channel. You can view messages from multiple channels simultaneously.

#### Unique Usernames
Username Authentication: Each client must have a unique username, ensuring a distinct identity within the DiSUcord network. You can enter your username through the client GUI.

#### Username Handling
The server keeps track of connected clients' usernames to prevent duplicate connections with the same name. This ensures a smooth and secure user experience.

#### Real-Time Communication
Message Sending: You can send messages to the channels you are subscribed to. Messages are delivered in real-time to all subscribers of the channel, including yourself.

#### Message History
While you can view messages sent after your subscription, DiSUcord does not display messages sent before your subscription to maintain message relevance.

#### Connection Management
Server Connection: Easily connect to the server by entering the server's IP address and port number via the client GUI. The connection status is displayed, providing immediate feedback.

#### Disconnection Handling
DiSUcord gracefully handles disconnections. You can disconnect from the system by pressing the disconnect button on the client GUI or closing the client window without causing crashes.

#### Server Management
Server Port Configuration: The server's port number is configurable through the Server GUI, allowing flexibility in network setup.

#### Multi-Client Support
The server supports multiple client connections simultaneously, ensuring efficient communication among users.

#### Detailed Logging
The Server GUI logs all server activities, including client connections, channel subscriptions, message transfers, and more. This comprehensive logging helps administrators monitor the system effectively.

#### Robust Error Handling
Graceful Closures: DiSUcord ensures that neither the server nor the client application crashes, even during abrupt closures. The system terminates processes gracefully.
Get Started
To use DiSUcord, follow these steps:

Download and compile the DiSUcord application on your computer.

1. Run the server application on one computer.

2. Run the client application on multiple computers.

3. Enter the server's IP address and port number via the client GUI to establish a connection.

4. Choose your username and start subscribing to channels.

5. Begin sending and receiving messages in real-time.

6. Enjoy the seamless messaging experience with DiSUcord!
