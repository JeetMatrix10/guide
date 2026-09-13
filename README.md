# Guide To-Do

A dependency-free full-stack project to-do list. It includes a responsive dashboard, filters, search, project summaries, task priorities, due dates, local JSON persistence, and a REST API.

## Run locally

```powershell
node server.js
```

Visit `http://localhost:3000`. The app creates `data/tasks.json` automatically on first run.

## API

- `GET /api/tasks` — list tasks (`?project=Work&status=active&q=design` supported)
- `POST /api/tasks` — create a task
- `PATCH /api/tasks/:id` — edit a task
- `DELETE /api/tasks/:id` — delete a task
- `GET /api/projects` — project summaries
- `GET /api/stats` — dashboard counts

## GitHub

Create an empty repository named `guide`, then run the commands in the handoff message after verifying the app.
