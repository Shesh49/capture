## **MERN Stack Note Taking App: Features and Setup** 📝✨

This document outlines the key features and steps to set up and run a full-stack note-taking application built with the **MERN Stack** (MongoDB, Express, React, Node).

-----

## **Key Features and Highlights**

  * **Full-Stack Architecture:** Built entirely using the **MERN Stack** for a cohesive development experience.
  * **Core CRUD Functionality:** Easily **create, update, and delete** notes, each consisting of a **title** and a **description**.
  * **Robust REST API:** Features a fully built and tested **REST API** backend.
  * **Real-World Concept:** Incorporates **Rate Limiting** using **Upstash Redis**, providing a simple introduction to this essential technique.
  * **Responsive Design:** Offers a **completely responsive UI** that adapts to various screen sizes.


-----

## **Local Setup Guide**

### **1. Environment Variables (`.env` Setup)** ⚙️

Create a `.env` file within the `/backend` directory and populate it with the following required variables:

| Variable | Description |
| :--- | :--- |
| **`MONGO_URI`** | Your connection string for the **MongoDB** database. |
| **`UPSTASH_REDIS_REST_URL`** | The REST URL for your **Upstash Redis** instance (used for rate limiting). |
| **`UPSTASH_REDIS_REST_TOKEN`** | The access token for your **Upstash Redis** instance. |
| **`NODE_ENV`** | Set to `development` for local execution. |

```
# Example .env content in /backend
MONGO_URI=<your_mongo_uri>
UPSTASH_REDIS_REST_URL=<your_redis_rest_url>
UPSTASH_REDIS_REST_TOKEN=<your_redis_rest_token>
NODE_ENV=development
```

-----

### **2. Running the Backend** 🛠️

Navigate to the backend directory, install dependencies, and start the server in development mode:

```bash
cd backend
npm install
npm run dev
```

-----

### **3. Running the Frontend** 💻

Navigate to the frontend directory, install dependencies, and launch the React development server:

```bash
cd frontend
npm install
npm run dev
```
