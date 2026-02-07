# Deploy Backend to Render

## Steps:

1. **Go to Render**: https://render.com/
2. **Sign up/Login** with GitHub
3. **Create New Web Service**
4. **Connect Repository**: Select `aks-45/parul`
5. **Configure Service**:
   - Name: `parul-backend`
   - Root Directory: `backend`
   - Environment: `Node`
   - Build Command: `npm install`
   - Start Command: `npm start`

6. **Add Environment Variables** (in Render dashboard):
   ```
   CLOUDINARY_CLOUD_NAME=db98qucif
   CLOUDINARY_API_KEY=487382933451982
   CLOUDINARY_API_SECRET=2G0z4co9li5cOgwmyc9l7SMt6Zw
   ```

7. **Deploy!**

8. **Copy the URL** (e.g., `https://parul-backend.onrender.com`)

9. **Update Frontend**: Replace `http://localhost:3001` with your Render URL in `src/components/WhatsAppMessenger.tsx`

## Your Credentials:
- Cloud Name: db98qucif
- API Key: 487382933451982
- API Secret: 2G0z4co9li5cOgwmyc9l7SMt6Zw
