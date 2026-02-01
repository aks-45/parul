# WhatsApp Message Sender Page

This is a complete WhatsApp messaging system for medical and pharmaceutical communications. The project includes both frontend and backend components.

## Features

- **Frontend**: React + TypeScript + Tailwind CSS
- **Backend**: Node.js + Express + WhatsApp Web.js
- **File Upload**: Excel/CSV file processing for bulk phone numbers
- **Real-time Messaging**: Direct WhatsApp integration
- **Responsive Design**: Works on all devices

## Quick Start

### Option 1: Automatic Setup
1. Run `install-backend.bat` to install backend dependencies
2. Run `start-app.bat` to start both frontend and backend

### Option 2: Manual Setup

#### Frontend Setup
```bash
npm install
npm run dev
```

#### Backend Setup
```bash
cd backend
npm install
npm run dev
```

## WhatsApp Authentication

1. Start the backend server
2. Open http://localhost:3001/api/whatsapp/status in your browser
3. Scan the QR code with your WhatsApp mobile app
4. Once authenticated, you can send messages through the frontend

## Usage

1. **Manual Entry**: Enter phone numbers separated by commas
2. **File Upload**: Upload Excel/CSV files with phone numbers
3. **Compose Message**: Write your message
4. **Send**: Click send to deliver messages via WhatsApp

## File Format

Excel files should have phone numbers in:
- First column, OR
- Column named 'phone', 'number', or 'mobile'

## URLs

- Frontend: http://localhost:5173
- Backend: http://localhost:3001
- Backend Health: http://localhost:3001/api/health
- WhatsApp Status: http://localhost:3001/api/whatsapp/status

## Original Design

The original project design is available at https://www.figma.com/design/ZYh8f0Kf439LihPFE2QRwm/WhatsApp-Message-Sender-Page.