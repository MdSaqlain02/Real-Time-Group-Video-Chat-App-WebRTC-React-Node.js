# Real-Time Group Video Chat App 💬🎥 demo-( https://drive.google.com/file/d/199Cu4tbMTLWGFp3k-FtR0SAl9bkWoG8T/view?usp=drivesdk )

A Zoom-like real-time group video chat application built using **WebRTC**, **React**, **Node.js**, and **Socket.IO**. This project demonstrates peer-to-peer video communication and real-time chat using modern web technologies.

## 🔍 Demo

**⚠️ Live demo not hosted due to peer-to-peer restrictions on unsecured connections. Please clone and run locally.**


### 📸 Screenshots
![Home Page](https://drive.google.com/file/d/1Br79oWdWzaZi0Tfe_dPW-O4spBwnXgE3/view?usp=drive_link)
![Video Chat](https://drive.google.com/file/d/1Y88L4GX5-YqgVqfyfNNoDLzG1PyEtpd4/view?usp=drive_link)
![Host Page](https://drive.google.com/file/d/1g39xL_JHLLJh424m8EwrXZ5P8E3tEHml/view?usp=sharing)
![Join Page](https://drive.google.com/file/d/1n3hongmtocordujjJiXZLdr5Jxq8GmpC/view?usp=drive_link)
[🎥 Watch Demo Video]( https://drive.google.com/file/d/199Cu4tbMTLWGFp3k-FtR0SAl9bkWoG8T/view?usp=drivesdk )

## Features
- ✅ Enables peer-to-peer video, audio, and chat communication without the need for a centralized server, using direct browser connections via WebRTC
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

2. Install dependencies
# For the server
cd server
npm install

# For the client
cd ../client
npm install

3. Run the application
Start the backend:
cd server
npm start

Start the frontend:
cd ../client
npm start

The app will be available at http://localhost:3000


