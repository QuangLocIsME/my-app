Hiểu rồi! Dưới đây là nội dung README bạn có thể sử dụng cho dự án của mình trên GitHub:

---

# Auth Page Example by Wuang Lok

## Overview

This project demonstrates a simple authentication page implementation using modern web technologies:

- **Frontend**: Next.js, Shadcn (UI framework)
- **Backend**: Bun (JavaScript runtime), Express.js
- **Database**: MongoDB

## Technologies Used

### Frontend
- **Next.js**: A popular React framework for building server-rendered applications.
- **Shadcn**: A UI component library used for building responsive and stylish interfaces.

### Backend
- **Bun**: A fast all-in-one toolkit for JavaScript & TypeScript apps.
- **Express.js**: A minimal and flexible Node.js web application framework.
- **MongoDB**: A NoSQL database for storing user data.

## Installation and Setup

### Prerequisites
- Node.js
- MongoDB
- Bun

### Clone the Repository
```bash
git clone [your-repo-url]
cd auth-page-example
```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Visit `http://localhost:3000` in your browser.

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   bun install
   ```
3. Configure MongoDB connection in `src/db.js`:
   ```javascript
   mongoose.connect('mongodb://localhost:27017/auth', {
     useNewUrlParser: true,
     useUnifiedTopology: true,
   });
   ```
4. Start the server:
   ```bash
   bun run src/index.js
   ```
5. The server will be running at `http://localhost:3001`.


