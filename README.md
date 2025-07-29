## MindDuel-App-backend
MindDuel-App-backend is a lightweight JSON server that powers the MindDuel-App trivia quiz application, providing RESTful API endpoints for user data, quiz questions, and results.

# Features
1. Instant REST API - Zero-configuration API endpoints
2. Database - Persistent data storage with db.json
3. CRUD Operations - Full support for Create, Read, Update, Delete
4. Deployed - Live API available 24/7

## Installation
First, ensure you have Node.js installed. Then install dependencies:

```bash
git clone https://github.com/your-username/MindDuel-App-Backend.git
cd MindDuel-App-Backend
npm install
```

# Usage
Start the server locally:

```bash
npm start
```

# API Endpoints:
GET    http://0.0.0.0:10000/users
POST   http://0.0.0.0:10000/users
PATCH  http://0.0.0.0:10000/users/:id
DELETE http://0.0.0.0:10000/users/:id

GET    http://0.0.0.0:10000/questions
GET    http://0.0.0.0:10000/questions?topic=Art&difficulty=easy

GET    http://0.0.0.0:10000/results
POST   http://0.0.0.0:10000/results

## Contributing
We welcome contributions to improve the MindDuel API!  
- Fork the repository
- Add test data to db.json
- Open a pull request

## License
MIT

## Author
MindDuel-App Team
