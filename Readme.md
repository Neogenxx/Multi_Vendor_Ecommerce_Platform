# Multi-Vendor E-Commerce Platform with Intelligent Recommendation System

## Project overview
A scalable multi-vendor marketplace that enables vendors to onboard, manage inventory and orders, and allows customers to browse, purchase, and receive AI-driven product recommendations. Built with Next.js, Node.js, and PostgreSQL; ML services for recommendations and an LLM-based shopping assistant planned.

## Libraries Used
- Frontend: Next.js, React, Tailwind CSS, Axios
- Backend: Node.js, Express, Sequelize/TypeORM
- Database: PostgreSQL, Redis
- ML: Python, Pandas, Scikit-learn, FastAPI
- DevOps: Docker, GitHub Actions
- Monitoring: Sentry

## Key Functions
- `auth/register`, `auth/login`, `auth/refresh` — user authentication
- `products/*` — product CRUD and search
- `orders/*` — create and manage orders
- `vendors/*` — vendor onboarding and product management
- `recommendations?user_id=` — ML service returning top K items
- `chatbot/query` — RAG + LLM conversational endpoint (post-auth)

## How to Run (dev)
1. Clone repo:
   ```
   git clone <repo-url>
   cd <repo-root>
   ```
