# Real-Time Group Video Chat App 💬🎥

A Zoom-like real-time group video chat application built using **WebRTC**, **React**, **Node.js**, and **Socket.IO**. This project demonstrates peer-to-peer video communication and real-time chat using modern web technologies.

## Features

- ✅ One-click video chat room creation
- ✅ Real-time group video and audio communication
- ✅ Text chat using WebRTC data channels
- ✅ Peer-to-peer connections via WebRTC (Mesh architecture)
- ✅ Signaling server using Socket.IO
- ✅ TURN/STUN server support for NAT traversal
- ✅ React front-end with simple and responsive UI

## 🛠️ Tech Stack

| Layer         | Technologies Used                                  |
|---------------|----------------------------------------------------|
| Frontend      | React, JavaScript, HTML, CSS                       |
| Backend       | Node.js, Express.js                                |
| Real-time     | WebRTC, Socket.IO, simple-peer                     |
| Signaling     | Socket.IO                                          |
| TURN/STUN     | (optional) Configurable with Twilio or Coturn      |


## How It Works

1. Each user opens the app and joins a room.
2. A Socket.IO server handles signaling.
3. WebRTC connects peers directly using `simple-peer`.
4. Audio/video streams and text messages are exchanged peer-to-peer.

##  Setup Instructions

### Prerequisites
- Node.js and npm installed
- Git installed
- Basic understanding of WebRTC and Socket.IO

### Steps

1. **Clone the Repository**
```bash
git clone https://github.com/MdSaqlain02/Real-Time-Group-Video-Chat-App-WebRTC-React-Node.js.git
cd Real-Time-Group-Video-Chat-App-WebRTC-React-Node.js


