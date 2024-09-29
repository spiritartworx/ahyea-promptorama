## Installation_Instructions

### Prerequisites

- **Node.js** (v16 or later)
- **MongoDB** (or access to a cloud MongoDB instance)
- **Elasticsearch** (for search functionality)
- **Docker** (for containerization and easy setup)

### Steps

1. Clone the repository:

```bash
git clone https://github.com/spiritartworx/ahyea-promptorama.git
cd ahyea-promptorama
```

2. Install dependencies for the backend and frontend:

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

3. Set up environment variables by creating a `.env` file in both the `backend` and `frontend` directories. Required variables include:
   - API keys for OpenAI (for GPT-3 and DALL-E).
   - Database connection strings (MongoDB).
   - Elasticsearch configuration.

4. Run the backend and frontend services:

```bash
# Start Backend
cd backend
npm run dev

# Start Frontend
cd ../frontend
npm run dev
```

5. Optionally, run services via Docker for a containerized setup:

```bash
docker-compose up
```
