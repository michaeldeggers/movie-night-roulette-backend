# Netflix Roulette

Description: Basic Idea of the site is a simple spinner that will choose a random movie to watch.

MVP: Simple Form for Choosing Genre and Querying Movies

Stretch: Allow Filters for Search

## Project Structure

```bash
.
├── README.md
├── movie-night-roulette-backend
│   ├── Makefile
│   ├── README.md
│   └── main.go
├── movie-night-roulette-frontend
│   ├── README.md
│   ├── package.json
│   ├── src
│   │   ├── App.css
│   │   ├── App.js
│   │   ├── App.test.js
│   │   ├── index.css
│   │   ├── index.js
│   │   ├── logo.svg
│   │   ├── serviceWorker.js
│   │   └── setupTests.js
│   └── yarn.lock
├── notes
│   └── NOTES.md
└── scratch
    └── tree.txt
```

## TODO

- Project
  - Dockerize All apps with `docker-compose.yml` in root directory.
- Frontend
  - Integrate with Backend Rest API
- Backend
  - Create API Server
  - Integreate API Server with Netflix API
- Stretch Goals
  - Allow Optional SSO Login
  - Store Viewing History
  - Allow User to Create / Write Comments about Choices
  - Integrate with Algorithm for Smart Selection Feature

