# Real-Time Group Video Chat App 💬🎥 demo-( https://drive.google.com/file/d/199Cu4tbMTLWGFp3k-FtR0SAl9bkWoG8T/view?usp=drivesdk )

A Zoom-like real-time group video chat application built using **WebRTC**, **React**, **Node.js**, and **Socket.IO**. This project demonstrates peer-to-peer video communication and real-time chat using modern web technologies.

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

## 🔍 Demo

**⚠️ Live demo not hosted due to peer-to-peer restrictions on unsecured connections. Please clone and run locally.**


### 📸 Screenshots
![Home Page](<img width="958" height="662" alt="Screenshot 2025-01-02 113116" src="https://github.com/user-attachments/assets/32d186bc-a002-4847-ac35-2c522e9a1d35" />)
![Video Chat](<img width="1897" height="875" alt="Screenshot 2024-12-06 065532" src="https://github.com/user-attachments/assets/5b19c03e-e950-406f-b7d5-35ebc2a4aa01" />
)

[🎥 Watch Demo Video]( https://drive.google.com/file/d/199Cu4tbMTLWGFp3k-FtR0SAl9bkWoG8T/view?usp=drivesdk )


