# Employee App Backend Integration

Express + MongoDB Atlas backend for the provided Employee App frontend (`dist/Frontend`, unchanged).

## API

| Method | Route | Purpose |
|---|---|---|
| GET | `/api/employeelist` | Get all employees |
| GET | `/api/employeelist/:id` | Get one employee |
| POST | `/api/employeelist` | Add employee `{name, location, position, salary}` |
| PUT | `/api/employeelist` | Update employee (body includes `_id`) |
| DELETE | `/api/employeelist/:id` | Delete one employee |

## Run

1. `npm install`
2. Copy `.env.example` to `.env`. Set `MONGO_URI` to your MongoDB Atlas connection string.
3. `node app.js`
4. Open http://localhost:3000
