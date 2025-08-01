# SigmaGPT

A full-stack ChatGPT clone built with the MERN stack (MongoDB, Express.js, React, Node.js) and integrated with OpenAI's API.

## 🚀 Features

- Real-time chat interface
- User authentication (JWT)
- Chat history persistence
- Markdown support for messages
- Responsive design with Ant Design
- WebSocket integration for real-time updates

## 🛠 Tech Stack

### Frontend
- React 19
- Vite (Build tool)
- Ant Design (UI Components)
- Socket.IO Client (Real-time communication)
- React Markdown (Message formatting)

### Backend
- Node.js with Express
- MongoDB with Mongoose
- JWT Authentication
- Socket.IO (Real-time communication)
- OpenAI API Integration
- Express Validator (Request validation)

## 📦 Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- MongoDB Atlas or local MongoDB instance
- OpenAI API key

## 🚀 Getting Started

### Backend Setup

1. Navigate to the Backend directory:
   ```bash
   cd Backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the Backend directory with the following variables:
   ```
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   OPENAI_API_KEY=your_openai_api_key
   PORT=5000
   ```

4. Start the development server:
   ```bash
   npm start
   ```

### Frontend Setup

1. Navigate to the Frontend directory:
   ```bash
   cd Frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the Frontend directory with the following variable:
   ```
   VITE_API_URL=http://localhost:5000
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173`

## 📂 Project Structure

```
SigmaGPT/
├── Backend/               # Backend server
│   ├── models/           # MongoDB models
│   ├── routes/           # API routes
│   ├── utils/            # Utility functions
│   ├── server.js         # Main server file
│   └── package.json      # Backend dependencies
│
├── Frontend/             # Frontend React app
│   ├── public/          # Static files
│   ├── src/             # React source code
│   ├── index.html       # Main HTML file
│   └── package.json     # Frontend dependencies
└── README.md            # This file
```

## 🔒 Environment Variables

### Backend
- `MONGODB_URI`: MongoDB connection string
- `JWT_SECRET`: Secret key for JWT token generation
- `OPENAI_API_KEY`: Your OpenAI API key
- `PORT`: Port for the backend server (default: 5000)

### Frontend
- `VITE_API_URL`: URL of the backend API (default: http://localhost:5000)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- OpenAI for their powerful API
- The MERN stack community
- All contributors and users of this project
