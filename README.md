# Personal API

A simple REST API built with Node.js/Express and deployed on a Linux VPS with Nginx reverse proxy.

## How to Run Locally

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
npm install
node index.js
```

The API will run on http://localhost:5000

## Endpoints

| Method | Endpoint | Response |
|--------|----------|----------|
| GET | / | `{"message": "API is running"}` |
| GET | /health | `{"message": "healthy"}` |
| GET | /me | `{"name": "...", "email": "...", "github": "..."}` |

## Live URL

https://angustask1.duckdns.org
