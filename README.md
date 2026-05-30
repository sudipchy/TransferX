# TransferX - P2P File Transfer System

A secure peer-to-peer file transfer system with resume capability.

## Features
- **5-Digit User IDs**: Unique identification for each user
- **P2P File Transfer**: Direct device-to-device transfer using WebRTC
- **Resume Capability**: Continue transfers from where you left off after disconnection
- **End-to-End Encryption**: Secure file transfers
- **Unlimited File System**: No file size restrictions

## Setup

1. Install dependencies:
```bash
npm run install-all
```

2. Start the application:
```bash
npm run dev
```

3. Open your browser to `http://localhost:3000`

## Usage
1. Register to get your 5-digit ID
2. Share your ID with the recipient
3. Select files to transfer
4. Enter recipient's ID
5. Transfer begins automatically
6. If disconnected, reconnect to resume from same percentage

## Technology Stack
- **Frontend**: React + Vite + TailwindCSS
- **Backend**: Node.js + Express + Socket.io
- **P2P**: WebRTC
- **Database**: SQLite
- **Encryption**: AES-256
