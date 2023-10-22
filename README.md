# Basic App with FastAPI and Strawberry

This is a basic web application built with FastAPI and Strawberry, demonstrating the integration of GraphQL with a FastAPI backend.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.7 or higher
- [FastAPI](https://fastapi.tiangolo.com/)
- [Strawberry](https://strawberry.rocks/)

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/DmitryDubovikov/FastAPI-GraphQL.git
   cd FastAPI-GraphQL
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Application:**

   ```bash
   uvicorn main:app --reload
   ```

This will start the FastAPI server, and your GraphQL API will be accessible at http://localhost:8000/graphql.

4. **Explore GraphQL API:**

Open your browser or any GraphQL client (such as GraphiQL) and navigate to http://localhost:8000/graphql. You can use the GraphQL playground to interact with your API.

### Sample Query:

   ```graphql
   query {
     user {
       name
       age
     }
   }
   ```