clubmanager/
│
├── server.js
├── package.json
├── database.db (criado automaticamente)
│
├── public/
│   ├── index.html
│   ├── times.html
│   ├── jogadores.html
│   └── style.css
{
  "name": "clubmanager",
  "version": "1.0.0",
  "description": "Sistema de gerenciamento de times",
  "main": "server.js",
  "scripts": {
    "start": "node server.js"
  },
  "dependencies": {
    "express": "^4.18.2",
    "sqlite3": "^5.1.6",
    "body-parser": "^1.20.2",
    "cors": "^2.8.5"
  }
}
