"# spring-boot-rest" 
1. Create Question POST /questions
body raw= {"title": "title sample","description": "description sample"}
2. Get paginated Questions GET /questions?page=0&size=2&sort=createdAt,desc
3. Create Answer POST /questions/{questionId}/answers
4. Get all answers of a Question GET /questions/{questionId}/answers
