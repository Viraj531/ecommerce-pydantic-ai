```mermaid
graph TD
A[User Browser] --> B[Frontend]
B --> C[FastAPI Backend]
C --> D[MongoDB]
C --> E[Pydantic AI Agent]
C --> F[LogFire]