# Meeting Minutes — Team 012-0

One file for the whole project. Add a new section at the top after every weekly TA meeting, and
push it **the same day as the meeting**. The scribe writes it, and it's a good idea to rotate
the scribe each week.

Minutes are graded on whether they accurately summarize the meeting. A list of names and "we
talked about the project" does not pass. Write down what was decided and who is doing what.

This file exists from Lab 8 onward, even before the first meeting: git does not track an empty
folder, so without a file `TeamMeetingLogs/` never reaches GitHub.

---

## Week 1 — `<meeting date>` (sample entry)

**Present:** all four members, and our TA
**Scribe:** Member 2

### Decisions made

- Build login and registration first, starting from our Lab 7 code.
- The `books` table has `book_id`, `title`, `author`, `owner` (references `users`) and
  `status`.
- Merge to `main` only through a pull request that another member has reviewed.

### Alternative actions/options discussed

- Pulling cover images from the Google Books API. Not for week 1. If we add it, we'll save the
  responses to the database first, so the app still works if the API goes down.
- One shared `index.js` versus splitting routes into files. We're staying with one file until
  it passes about 300 lines.

### Follow-up items, including agreed-on roles and responsibilities

| Item | Owner | Due |
| --- | --- | --- |
| Registration page and route, with hashed passwords | Altaf | Mon |
| Login, logout and sessions | Member 2 | Tue |
| `create.sql` for `users` and `books`, plus sample rows in `insert.sql` | Member 3 | Mon |
| Project board: one story per feature, each with an owner | Member 4 | Fri |

---

## Template — copy this above the previous week

## Week N — `<meeting date>`

**Present:** `<names>`
**Scribe:** `<name>`

### Decisions made

- `<...>`

### Alternative actions/options discussed

- `<...>`

### Follow-up items, including agreed-on roles and responsibilities

| Item | Owner | Due |
| --- | --- | --- |
| `<...>` | `<name>` | `<day>` |
