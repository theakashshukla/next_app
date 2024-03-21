# Next.js App with Docker & CI/CD

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


## Running the Application on Docker

1. Clone this repository to your local machine:

```bash
git clone https://github.com/theakashshukla/next_app.git
```

2. Navigate to the project directory:

```bash
 cd next_app
```

3. Start the application using Docker Compose:

```bash
docker-compose up --build
```

4. Open your browser and navigate to `http://localhost:3000` to view the application.


5. Stop the application using Docker Compose:

```bash
docker-compose down
```

6. Remove the application using Docker Compose:

```bash
docker-compose down --volumes
```





