AI Image Generation with React, Node, Express & Replicate
This project contains both the frontend (React) and backend (Node + Express) of an AI image generation app, powered by Replicate.

I streamed building this app on my Twitch channel.

Running the App
You need a valid, paid Replicate account + API key to use the Replicate API.

Install both the frontend and backend dependencies and start both development servers.

Frontend
npm install
npm run dev
Backend
cd backend
npm install
npm run dev
Create a .env file in the /backend folder and store the following keys in it:

JWT_SECRET_KEY=supersecret
REPLICATE_API_TOKEN=<YOUR REPLICATE API KEY>