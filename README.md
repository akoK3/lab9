# Pro Video Room (Zoom Clone)

## What the app does
This is a Zoom-like web application that enables users to create and join video meetings. It provides real-time peer-to-peer video, audio communication, and user presence logic using WebRTC (PeerJS) and WebSocket (Socket.io) technologies, built on top of a Node.js and Express backend.

## How to install and run it
1. Ensure you have Node.js installed on your system.
2. Clone or download the project files.
3. Open a terminal in the project directory.
4. Run `npm install` to install all necessary dependencies.
5. Run `node server.js` to start the web server.
6. The server will be running at `http://localhost:3000`.

## How to use it
- **Create a meeting**: Open your browser and navigate to `http://localhost:3000`. The server will automatically generate a unique meeting room ID, redirect you to it, and request access to your camera and microphone.
- **Join a meeting**: Copy the URL from your address bar once you are in a room and share it with others. They can paste it into their browser to join the same meeting room.
- **In-meeting controls**: Use the control bar to mute/unmute your audio, stop/start your video, and leave the room when you are finished.
