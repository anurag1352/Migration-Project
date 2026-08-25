# DevOps Shack — Jenkins to GitHub Actions Migration Demo

A colorful Express application for demonstrating a Jenkins pipeline migration to GitHub Actions.

## Run locally

```bash
npm install
npm test
npm start
```

Open `http://localhost:8080`.

## Run with Docker

```bash
docker build -t devopsshack/migration-demo .
docker run --rm -p 8081:8080 devopsshack/migration-demo
```

## Endpoints

- `/` — migration dashboard
- `/health` — application health
- `/api/migration` — migration demo metadata
