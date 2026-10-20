# Shelf — Team 012-0

> **This is a sample repository**, made by your TA to show how a CSCI 3308 project repo is
> laid out after Lab 8. Team 012-0 and the Shelf app are made up. Copy the *structure*, not the
> content.

Shelf lets the residents of one dorm floor lend each other books. You list what's on your
shelf, browse everyone else's, and send a borrow request. Shelf keeps track of who has what.

## Contributors

| Name | GitHub |
| --- | --- |
| Altaf Barelvi | [ctrlaltaf](https://github.com/ctrlaltaf) |
| Member 2 | `<github-username>` |
| Member 3 | `<github-username>` |
| Member 4 | `<github-username>` |

## Technology stack

Node.js and Express, Handlebars, PostgreSQL, Docker Compose, bcrypt, express-session, Mocha and
Chai, Render.

## Repository structure

The root of the repo holds **only** these four entries (Lab 8, item 8):

```
TeamMeetingLogs/        minutes of every weekly TA meeting, in one file updated each week
MilestoneSubmissions/   the project proposal and every later course document
ProjectSourceCode/      the application: code, Docker setup, tests, and its .gitignore
ReadMe.md               this file
```

Two things that are easy to get wrong:

- **Git does not track empty folders.** `TeamMeetingLogs/` already has a file in it, which is
  why it shows up on GitHub. An empty folder exists on your laptop and is missing from the repo.
- **The `.gitignore` lives in `ProjectSourceCode/`, not at the root.** When you create the repo
  on GitHub, leave *Add a README*, *Add .gitignore* and *Choose a license* all unticked. Each
  one adds a file at the root that doesn't belong there.

## Prerequisites

- Docker Desktop, running
- Git

## Running locally

From `ProjectSourceCode/`:

```bash
docker compose up -d
```

Then open http://localhost:3000. *(The app doesn't exist yet. This section gets filled in as
the project is built.)*

## Running the tests

*(Added in Lab 10.)*

## Deployed application

*(Added in Lab 12.)*
