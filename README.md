# Full Stack Open exercises

My solutions to exercises from [Full Stack Open](https://fullstackopen.com/), the University of Helsinki's open course on modern web development, parts 1–3 (2022).

| Folder | Course part | What it is |
|---|---|---|
| `part1/` | 1 | Introductory React exercises |
| `unicafe/` | 1 | Unicafe feedback app with statistics (React) |
| `anecdotes/` | 1 | Anecdotes app with voting (React) |
| `notes/` | 2 | Notes app (React) |
| `phonebook/` | 2 | Phonebook app (React, axios) |
| `countries/` | 2 | Country search with current weather (React; REST Countries and OpenWeatherMap APIs) |
| `part3/` | 3 | Notes REST API (Node.js, Express) |

## Running an exercise

Each folder is a separate npm project: `npm install`, then `npm start` (`npm run dev` for `part3/`).

- `countries/` needs an OpenWeatherMap API key in the `REACT_APP_API_KEY` environment variable.
- `notes/` and `phonebook/` were later pointed at backends from part 3, so they don't run on their own.
