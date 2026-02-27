# Finance-Tracker
A finance tracker

Project Structure Reference
/app       — Vue frontend
/server    — Fastify backend
/data      — SQLite DB (docker volume)
Dockerfile
docker-compose.yml

finance-tracker/
│
├── app/                        # Vue
│   ├── src/
│   │   ├── components/
│   │   ├── views/
│   │   ├── stores/
│   │   ├── services/
│   │   ├── locales/
│   │   └── router/
│   └── dist/
│
├── server/
│   ├── src/
│   │   ├── routes/
│   │   ├── domain/             # business logic
│   │   ├── db/
│   │   ├── plugins/
│   │   ├── auth/
│   │   └── utils/
│
├── data/                       # mounted SQLite volume
│
├── Dockerfile
├── docker-compose.yml
└── README.md
