# Deploy WhatsApp Messenger to Render

## Quick Deploy Steps:

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```

### 2. Deploy on Render
1. Go to [render.com](https://render.com)
2. Sign up/Login with GitHub
3. Click "New" → "Static Site"
4. Connect your GitHub repository
5. Configure:
   - **Build Command**: `npm install && npm run build`
   - **Publish Directory**: `dist`
   - **Auto-Deploy**: Yes

### 3. Environment Variables (Optional)
No environment variables needed for this static site.

## Alternative: Manual Deploy

### Option 1: Build and Upload
```bash
npm install
npm run build
```
Then upload the `dist` folder to any static hosting service.

### Option 2: Netlify Drag & Drop
1. Run `npm run build`
2. Go to [netlify.com](https://netlify.com)
3. Drag the `dist` folder to deploy

## Features Included:
- ✅ Excel file upload and parsing
- ✅ Bulk WhatsApp messaging
- ✅ Custom footer support
- ✅ Responsive design
- ✅ Real-time status updates
- ✅ Auto-prefix Indian numbers with 91

## Live Demo:
Your app will be available at: `https://your-app-name.onrender.com`