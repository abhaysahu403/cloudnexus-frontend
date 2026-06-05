# Cloud Nexus HR - Frontend

React-based HR Management Dashboard

## Setup

```bash
npm install
npm start
```

## Environment Variables

Create `.env`:
```
REACT_APP_API_URL=http://backend-ip:5000/api
```

## Docker

```bash
docker build -t cloud-nexus-frontend .
docker run -p 3000:3000 cloud-nexus-frontend
```
