# FastApiSqlAlchemy 
Demonstrates a REST API for a SQL Database. The REST web service layer is implemented 
using the FastAPI and Pydantic python libraries. 
The data access layer is implemented using SQLAlchemy

## Docker Deployment Steps
1. docker build -t fast-api-sa .
2. docker tag fast-api-sa dcha22/fast-api-sa
3. docker push dcha22/fast-api-sa
4. docker pull dcha22/fast-api-sa
4. docker run --name FastApiSqlAlchemy -p 8081:80 -d dcha22/fast-api-sa
