# Collaborative Whiteboard

A web-based whiteboard application built to provide an interactive digital canvas for drawing, sketching, and visual collaboration.

## Overview

Collaborative Whiteboard is a full-stack web application featuring an interactive drawing canvas and a dedicated backend. It provides drawing tools and canvas-based functionality through a clean user interface.

## Features

- **Interactive Drawing Canvas:** Draw and create elements on a digital canvas.
- **Drawing Tools:** Work with different drawing tools, including lines and other supported shapes.
- **Custom Styling:** Configure drawing properties such as stroke color, fill color, and size.
- **Canvas Rendering:** Uses HTML Canvas and Rough.js for sketch-style rendering.
- **Backend Architecture:** Separate Node.js and Express.js backend.
- **Data Management:** MongoDB integration for backend data persistence.

## Tech Stack

| Category | Technologies |
|---|---|
| Frontend | React.js, JavaScript |
| Styling | Tailwind CSS |
| Canvas | HTML Canvas, Rough.js |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Version Control | Git, GitHub |

## Project Structure

```text
Collabrative-Whiteboard/
│
├── public/
├── src/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
├── package.json
└── README.md
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/nakultiwari10/Collabrative-Whiteboard.git
cd Collabrative-Whiteboard
```

### 2. Setup Frontend

```bash
npm install
npm start
```

The frontend will run at:

```text
http://localhost:3000
```

### 3. Setup Backend

Open another terminal:

```bash
cd backend
npm install
```

Create a `.env` file in the backend directory and configure your environment variables.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

Start the backend using the start command configured in the backend `package.json`.

## Environment Variables

Configure the required environment variables locally. Never commit your `.env` file or expose database credentials.

## Screenshots

Add application screenshots here to demonstrate the interface and drawing functionality.

## Future Improvements

- Real-time multi-user collaboration.
- Improved canvas controls and drawing features.
- Enhanced user experience.
- Cloud deployment and scalability.

## Author

**Nakul Tiwari**

GitHub: [@nakultiwari10](https://github.com/nakultiwari10)

---

If you find this project useful, consider giving the repository a star!
