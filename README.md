# growth-edge-infra-1780125863790

An Express + PostgreSQL project: growth-edge-infra-1780125863790

## Stack

- **Runtime**: Node.js
- **Framework**: Express
- **Database**: PostgreSQL (via pg)
- **Deploy**: railway
- **Auth**: JWT (jsonwebtoken + bcrypt)
- **Cache**: Redis (ioredis)

## Getting Started

```bash
cp .env.example .env
npm install
npm run dev
```

## API Endpoints

- `GET /health` — Health check
- `POST /auth/login` — Login and receive JWT

## Environment Variables

See `.env.example` for required variables.
