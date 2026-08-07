devmind/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── features/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── store/
│   │   ├── types/
│   │   ├── utils/
│   │   ├── routes/
│   │   ├── App.tsx
│   │   └── main.tsx
│   └── package.json
│
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── services/
│   │   ├── repositories/
│   │   │
│   │   ├── ai/
│   │   │   ├── llm/
│   │   │   ├── embeddings/
│   │   │   ├── rag/
│   │   │   ├── reranking/
│   │   │   ├── prompts/
│   │   │   └── tools/
│   │   │
│   │   ├── middleware/
│   │   ├── validators/
│   │   ├── models/
│   │   ├── utils/
│   │   ├── app.ts
│   │   └── server.ts
│   │
│   ├── tests/
│   └── package.json
│
├── workers/
│   ├── document-worker/
│   └── embedding-worker/
│
├── database/
│   ├── migrations/
│   ├── seeds/
│   └── schema/
│
├── docs/
│   ├── architecture/
│   ├── api/
│   ├── database/
│   └── ai/
│
├── docker/
│   ├── backend.Dockerfile
│   ├── frontend.Dockerfile
│   └── worker.Dockerfile
│
├── docker-compose.yml
├── .env.example
├── .gitignore
├── package.json
└── README.md