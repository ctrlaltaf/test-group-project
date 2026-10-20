# ProjectSourceCode

Everything that makes the app run lives here: code, Docker setup, database scripts and tests.
Nothing else in the repo is application code.

## Recommended layout

From the course project guide. Lab 8 needs only the `.gitignore`. The rest arrives as you build.

```
ProjectSourceCode/
├─ docker-compose.yaml
├─ .gitignore
├─ package.json
├─ src/
│  ├─ index.js
│  ├─ views/
│  │  ├─ layouts/main.hbs
│  │  ├─ pages/home.hbs, login.hbs, register.hbs
│  │  └─ partials/header.hbs, footer.hbs
│  ├─ resources/
│  │  ├─ css/style.css
│  │  ├─ js/script.js
│  │  └─ img/
│  └─ init_data/
│     ├─ create.sql
│     └─ insert.sql
└─ test/
   └─ server.spec.js
```

`node_modules/` and `.env` exist on your laptop but are never committed. The `.gitignore` here
keeps them out.

## Things to know

- **The `.gitignore` belongs in this folder, not at the repo root.** The root holds only
  `TeamMeetingLogs/`, `MilestoneSubmissions/`, `ProjectSourceCode/` and `ReadMe.md`.
- **Run `docker compose` from this folder.** That's where `docker-compose.yaml` is. From the
  repo root, compose can't find it.
- **`init_data/` only runs on an empty database volume.** Change `create.sql` after the first
  `docker compose up` and nothing happens until `docker compose down -v`.
- **You may reuse your own lab code.** Code written by team members for this course's labs, and
  the provided lab starter code, are allowed. Everything else is written by the team.
