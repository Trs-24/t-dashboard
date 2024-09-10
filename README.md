# Test App

**Stack:**
- React.js
- Tailwindcss
- Vite
- Redux Toolkit
- Express.js
- MongoDB

## Scripts

## How to run

1. ``npm install`` install dependencies for a backend app.

2. ``cd client`` go into the client folder.

3. ``npm install`` install dependencies for a client app.

4. ``cd ..`` go back into the root folder.

5. Add .env to the root folder:
```
PORT=3000
MONGO_URL=mongodb+srv://admin:123456ad@cluster0.6fwe8.mongodb.net/t-dashboard?retryWrites=true&w=majority
JWT_SECRET=wer+234+_aU{23w/w]fkc
```
6``npm run dev`` concurrently run backend and frontend apps.