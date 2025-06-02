# n8n local stack

n8n Credentials:

QdrantApi account:

API key from `QDRANT__SERVICE__API_KEY` in .env file.
Qdrant URL: `http://qdrant:63333

Then check the dashboard: http://localhost:63333/dashboard

Header Auth Qdrant:

- Name: `api-key`
- Value: `QDRANT__SERVICE__API_KEY` from the .env file.

Header Auth Crawl4ai:

- Name: `Authorization`
- Value: `Bearer CRAWL4AI_API_TOKEN` from the .env file.

If traefik running on `proxy` docker network, you can uncomment the labels.