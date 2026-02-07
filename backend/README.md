# Backend for Image Upload

## Setup Instructions

### 1. Get Cloudinary Account (Free)
1. Go to https://cloudinary.com/
2. Sign up for a free account
3. Get your credentials from the dashboard:
   - Cloud Name
   - API Key
   - API Secret

### 2. Configure Environment Variables
Edit the `.env` file and add your Cloudinary credentials:
```
PORT=3001
CLOUDINARY_CLOUD_NAME=your_cloud_name_here
CLOUDINARY_API_KEY=your_api_key_here
CLOUDINARY_API_SECRET=your_api_secret_here
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Run the Server
```bash
npm start
```

The server will run on http://localhost:3001

## API Endpoints

- `POST /upload` - Upload an image file
- `GET /health` - Health check

## Deploy to Render

1. Push your code to GitHub
2. Go to https://render.com/
3. Create a new Web Service
4. Connect your GitHub repository
5. Set the following:
   - Build Command: `cd backend && npm install`
   - Start Command: `cd backend && npm start`
6. Add environment variables in Render dashboard
7. Deploy!
