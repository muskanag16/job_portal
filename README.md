# Hire Hub

A comprehensive job seeking and posting platform that connects job seekers with recruiters.

> **Important Note:** We're using free-tier servers which may need a warm-up:
> 1. First open the backend URL and wait for it to load
> 2. Then access the frontend URL for the best experience
> 3. If experiencing delays, please refresh both URLs

## ✨ Features

### 👤 For Job Seekers
- Account creation and management
- Job search with advanced filtering
- Save interesting job postings
- Apply to jobs
- Profile customization
- Resume upload and management

### 💼 For Recruiters
- Company registration and profile management
- Job posting creation and management
- Access to applicant details (name, phone, resume)
- Applicant tracking and management
## 🛠️ Tech Stack

- Frontend: React.js
- Backend: Node.js
- Database: MongoDB
- Cloud Storage: Cloudinary
- AI Integration: Google Gemini

## ⚙️ Environment Variables

Create a `.env` file in the root directory:

```env
PORT=8000
MONGO_URI=mongodb+srv://your_username:your_password@cluster0.example.mongodb.net/
SECRET_KEY=your_secret_key
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret
CLOUD_NAME=your_cloudinary_cloud_name
GIMINIAI_API=your_gemini_api_key
FRONTEND_URL=https://hire-hub-chandan.vercel.app
```

## 🔧 Frontend Configuration

Update the backend URL in `client/src/utils/constant.js`:

```javascript
const BASE_URL = "https://hire-hub-psi.vercel.app/api/v1";
```




## 💻 Local Development

1. Clone the repository
2. Install dependencies:
```bash
# Backend
cd backend
npm install

# Frontend
cd client
npm install
```

3. Start the development servers:
```bash
# Backend
npm run dev

# Frontend
npm run dev
```


