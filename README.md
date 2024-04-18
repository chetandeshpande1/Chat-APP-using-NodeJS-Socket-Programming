# Chat-APP-using-NodeJS-Socket-Programming
A simple chat application built with Node.js, Express, Socket.IO, Mongoose and MongoDB. Users can enter name, send and receive real-time messages, and view the chat history. Features include user authentication, message persistence.  This project demonstrates the use of web sockets for real-time communication and MongoDB for data storage. It provides a basic yet functional chat interface that can be easily integrated into other web applications.

# How to run this app:

1. **Install Dependencies**: Run `npm install` in the project directory to install all required dependencies.
2. **Start the Server**: Run `node server.js` to start the server. This will start the WebSocket server and allow clients to connect.
3. **Open Client Interface**: Open the `client.html` file in a web browser. This will load the chat client interface.
4. **Enter Username**: In the login form, enter your desired username, then click "Start Chatting" to join the chat room.
5. **Send Messages**: Type your messages in the input field at the bottom of the chat interface and click "Send" to send messages to the chat room.
6. **Join Multiple Users**: Open multiple instances of the `client.html` file in different tabs or windows to simulate multiple users for chatting.
7. **Chat in Real-Time**: Messages sent by any user will be displayed in real-time to all users in the same chat room.
By following these steps, you can run the chat app locally and interact with other users in real-time.
