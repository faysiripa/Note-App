## Deployment Link

https://note-app-3hn7.onrender.com/

---

## App Features Overview

- Full-Stack App Built with the MERN Stack (MongoDB, Express, React, Node)
- Create, Update, and Delete Notes with Title & Description
- Build and Test a Fully Functional REST API
- Rate Limiting with Upstash Redis 
- Completely Responsive UI

---

## .env Setup

### Backend (/backend)

```bash
MONGO_URI=<your_mongo_uri>

UPSTASH_REDIS_REST_URL=<your_redis_rest_url>
UPSTASH_REDIS_REST_TOKEN=<your_redis_rest_token>

NODE_ENV=development
```

## Run the Backend

```bash
cd backend
npm install
npm run dev
```

## Run the Frontend

```bash
cd frontend
npm install
npm run dev
```
