# node-mongo-user-api

# Node.js + MongoDB User API

This is a simple Express API that connects to MongoDB and returns user data. It supports retrieving a user by ID and clearly distinguishes between:

- User found and over 21 → ✅ 200 OK
- User found but under 21 → 🚫 403 Forbidden
- User not found → ❌ 404 Not Found

### To Run Locally

1. Clone the repo
2. Run `npm install`
3. Add a `.env` file with your MongoDB URI
4. Run `node app.js`
