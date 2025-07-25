# VIBELINK

A modern, full-stack real-time chat application with user authentication, profile management, and media support. Built with Node.js, Express, MongoDB, React, and Vite.

## Features
- Real-time messaging
- User authentication (JWT-based)
- Profile management with avatar upload (Cloudinary)
- Responsive UI with React and Tailwind CSS
- Sidebar with chat list and user search
- Settings and profile pages
- Skeleton loaders for smooth UX

## Tech Stack
- **Backend:** Node.js, Express, MongoDB, Mongoose
- **Frontend:** React, Vite, Tailwind CSS
- **Media Storage:** Cloudinary
- **Authentication:** JWT

## Getting Started

### Prerequisites
- Node.js (v16+ recommended)
- npm
- MongoDB Atlas account (or local MongoDB)
- Cloudinary account

### Installation

#### 1. Clone the repository
```sh
git clone https://github.com/yourusername/CHAT-APP.git
cd CHAT-APP
```

#### 2. Setup Backend
```sh
cd backend
npm install
```

Create a `.env` file in the `backend` directory with the following variables:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Start the backend server:
```sh
npm start
```

#### 3. Setup Frontend
```sh
cd ../frontend
npm install
npm run dev
```

The frontend will typically run at [http://localhost:5173](http://localhost:5173).

## Usage
- Register or log in to start chatting.
- Update your profile and avatar in the profile/settings page.
- Start new chats from the sidebar.

## Environment Variables
| Variable                | Description                        |
|------------------------ |------------------------------------|
| MONGODB_URI             | MongoDB connection string           |
| JWT_SECRET              | Secret for JWT signing              |
| CLOUDINARY_CLOUD_NAME   | Cloudinary cloud name               |
| CLOUDINARY_API_KEY      | Cloudinary API key                  |
| CLOUDINARY_API_SECRET   | Cloudinary API secret               |

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

## License
[MIT](LICENSE)

---

**Made with ❤️ for modern chat experiences.**
