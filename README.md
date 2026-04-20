# HNG-INTERNSHIP-STAGE1

A minimal REST API built with Node.js and Express, deployed on a Linux VPS behind an Nginx reverse proxy.

## How to Run Locally

**Prerequisites:** Node.js installed

```bash
git clone https://github.com/yourusername/personal-api.git
cd personal-api
npm install
npm start
```
API will be available at http://localhost:3000

## Endpoints

### GET /
```json
{ "message": "API is running" }
```

### GET /health
```json
{ "message": "healthy" }
```

### GET /me
```json
{
  "name": "Your Full Name",
  "email": "you@example.com",
  "github": "https://github.com/yourusername"
}
```

## Live Deployment

http://74.234.168.57
