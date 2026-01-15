# Hello World Express TypeScript App

The simplest Express TypeScript app that displays "Hello World" on a webpage.

## Setup (Local)

1. Install dependencies:
```bash
npm install
```

2. Run the app:
```bash
npm start
```

3. Open your browser and navigate to `http://localhost:3000`

You should see "Hello World" displayed on the page!

## Setup (Docker)

1. Build and run with Docker Compose:
```bash
docker-compose up
```

2. Open your browser and navigate to `http://localhost:3000`

To stop the container:
```bash
docker-compose down
```

### Alternative: Using Docker directly

Build the image:
```bash
docker build -t hello-world-express .
```

Run the container:
```bash
docker run -p 3000:3000 hello-world-express
```
