# github-actions-demo

Express REST API for managing tasks, designed to demonstrate GitHub Actions CI/CD.

## Setup

```bash
npm install
```

## Run

```bash
npm start
# Server runs on http://localhost:3000
```

## Test

```bash
npm test          # runs Jest with coverage
npm run lint      # runs ESLint
```

## API Endpoints

| Method | Path         | Description          |
|--------|-------------|----------------------|
| GET    | /           | API info             |
| GET    | /health     | Health check         |
| GET    | /tasks      | List all tasks       |
| GET    | /tasks/:id  | Get task by ID       |
| POST   | /tasks      | Create task `{title}`|
| DELETE | /tasks/:id  | Delete task by ID    |

## Git Init & Push

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/<your-user>/github-actions-demo.git
git push -u origin main
```
