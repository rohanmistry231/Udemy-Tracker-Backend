# Udemy Tracker Backend

This is the backend server for the **Udemy Tracker Application**, built using Node.js, Express.js, and MongoDB. It manages course data, tracks progress, and syncs updates between local IndexedDB and MongoDB Cloud.

---

## Features

- RESTful API for managing Udemy courses.
- Integration with Udemy API for course data retrieval.
- CRUD operations for courses and notes.
- Local storage syncing with MongoDB Cloud.
- IndexedDB for offline-first support.
- Scalable backend using Node.js and Express.js.

---

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Getting Started

Follow these instructions to set up and run the project locally.

---

## Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account for cloud database setup
- Udemy Client API credentials

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/udemy-tracker-backend.git
   cd udemy-tracker-backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file and configure it as per the [Environment Variables](#environment-variables) section.

4. Start the development server:
   ```bash
   npm run dev
   ```

5. The server will run at `http://localhost:5000` by default.

---

## Environment Variables

Create a `.env` file in the root directory and configure the following:

```env
PORT=5000
MONGO_URI=your-mongodb-atlas-uri
```

---

## Usage

- Retrieve Udemy courses and sync them with MongoDB.
- Manage course notes, progress, and categories.
- Sync updates between IndexedDB and MongoDB.

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.