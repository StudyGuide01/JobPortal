# Job Portal Project

This is a Job Portal application where users can search, post, and apply for jobs. The project includes both backend and frontend components. The backend is built with Node.js and connects to MongoDB to store job-related data. Additionally, Cloudinary is used for handling media (images, etc.) related to the job posts.

## Prerequisites

Before you begin, make sure you have the following installed:

- **Node.js** (LTS version)
- **MongoDB** (running locally on port 27017)
- **Cloudinary account** for media management

## Environment Variables

You will need to set up the following environment variables to configure the app correctly:

- `PORT`: Port number where the app will run (default is `8000`).
- `MONGO_URL`: MongoDB connection URL (e.g., `mongodb://localhost:27017/Job_Portal`).
- `USER_SECRET_KEY`: Secret key used for securing user sessions (use your own secret key).
- `CLOUDINARY_NAME`: Cloudinary cloud name for media storage (e.g., `do7pydtrf`).
- `CLOUDINARY_API_KEY`: Cloudinary API key.
- `CLOUDINARY_API_SECRET`: Cloudinary API secret.

## Installation

1. Clone the repository:


## Install the dependencies:
npm install


## Set up the environment variables in a .env file:
PORT=8000
MONGO_URL=mongodb url 
USER_SECRET_KEY=your-secret-key
CLOUDINARY_NAME=do7pydtrf
CLOUDINARY_API_KEY=your-api-key
CLOUDINARY_API_SECRET=your-api-secret


