# Jamify – A Collaborative Music Streaming App 🎧

Jamify is a real-time collaborative music streaming platform where users can create rooms, add songs, upvote favorites, and chat — making shared listening fun and democratic!

## 🔑 Key Features

- 🎵 Create & Join Music Rooms
- ➕ Add Songs to Queue (via YouTube API)
- 👍 Upvote Songs to Decide the Next Track
- 💬 Real-time Chatbox for Every Room
- 🔄 Live Updates via WebSockets

## 🛠️ Tech Stack

- **Frontend**: React, Next.js, TailwindCSS
- **Backend**: WebSocket, Redis, PostgreSQL
- **ORM**: Prisma
- **Auth**: NextAuth (OAuth)
- **APIs**: YouTube API for streaming

## 🚀 Local Setup

```bash
pnpm install
# Set up your .env file based on .env.example
pnpm run dev
