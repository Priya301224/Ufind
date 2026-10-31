
# UFind – Campus Lost and Found Platform

UFind is a centralized web application designed to help college students report, search for, claim, and recover lost belongings on campus. It replaces scattered WhatsApp messages and informal reporting methods with an organized platform.

## Live Demo

**Backend (Render):** [UFind API](https://your-render-service-name.onrender.com)

> Replace the placeholder with your actual Render deployment URL.

## Overview

Students frequently lose personal belongings in classrooms, libraries, cafeterias, hostels, laboratories, and other campus locations.

Existing methods, such as WhatsApp groups, social media posts, and security desks, make it difficult to search for items, contact their owners, and track successful returns.

UFind provides a centralized platform where students can:
- Report lost and found items.
- Upload photographs and descriptions.
- Share item locations.
- Search and filter reported items.
- Claim items and communicate with other users.
- Track item recovery status.

## Key Features

- **User Authentication:** Secure registration, login, and profile management.
- **Lost and Found Posts:** Create reports with photographs, descriptions, categories, and locations.
- **Search and Filtering:** Find items using keywords, categories, locations, and status.
- **Claim Management:** Submit claims and view claim history.
- **Notifications and Chat:** Receive updates and communicate with other users.
- **Recovery Management:** Mark successfully returned items as Recovered.
- **Responsive Interface:** Access the platform through desktop and mobile browsers.
- **Input Validation:** Validate submitted information and prevent incomplete entries.

## Technology Stack

| Technology | Purpose |
|---|---|
| MongoDB | Database |
| Express.js | Backend Framework |
| React.js | Frontend Library |
| Node.js | Runtime Environment |
| Socket.IO | Real-Time Communication |
| Cloudinary | Image Management |
| HTML, CSS, JavaScript | Web Development |

## Project Structure

```text
UFind/
├── client/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── server/
│   ├── src/
│   └── package.json
│
├── .gitignore
└── README.md
```

## Installation and Setup

### Prerequisites

- Node.js and npm
- MongoDB
- Git

### 1. Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd UFind
```

### 2. Install Backend Dependencies

```bash
cd server
npm install
```

### 3. Install Frontend Dependencies

```bash
cd ../client
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the backend directory.

**Backend `.env`:**

```env
PORT=<YOUR_BACKEND_PORT>
MONGODB_URI=<YOUR_MONGODB_URI>
CLIENT_URL=<YOUR_FRONTEND_URL>
```

**Frontend `.env`:**

```env
VITE_API_URL=<YOUR_BACKEND_API_URL>
```

> Use the exact environment variable names required by your source code. Never upload credentials or API secrets to GitHub.

### 5. Run the Application

**Backend:**

```bash
npm run dev
```

**Frontend:**

```bash
npm run dev
```

Run the commands from their respective project directories.

## Deployment

### Backend Deployment – Render

1. Push the backend code to GitHub.
2. Create a new Web Service on Render.
3. Connect your GitHub repository.
4. Select the backend root directory.
5. Configure the build and start commands.
6. Add the required environment variables.
7. Deploy the application.

**Render Backend URL:**

```text
https://your-render-service-name.onrender.com
```






## References

- [MongoDB Documentation](https://www.mongodb.com/docs/)
- [React Documentation](https://react.dev/)
- [Node.js Documentation](https://nodejs.org/docs/)
- [Express.js Documentation](https://expressjs.com/)
- [Socket.IO Documentation](https://socket.io/docs/v4/)
- [Cloudinary Documentation](https://cloudinary.com/documentation/)
- [GitHub Documentation](https://docs.github.com/)
- [MDN Web Docs](https://developer.mozilla.org/)

---

**UFind – Making campus lost-and-found simpler, more organized, and easier to access.**
