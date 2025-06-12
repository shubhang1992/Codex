# Supabase Login Demo

This demo shows how to implement basic sign up and login flows using [Supabase](https://supabase.com) for authentication. The backend is a small Express server that forwards signup and login requests to Supabase.

## Setup

1. Copy `.env.example` to `.env` and fill in your Supabase project URL and anon key.
2. Install dependencies with `npm install` (requires Node 18+).
3. Start the server using `npm start`. The HTML pages will be served on the same port.
4. Open `http://localhost:3000/index.html` in your browser to sign up or log in.

## Files
- `index.html` – Home page with links to sign up or log in
- `signup.html` – Sign up form posting to the `/signup` endpoint
- `login.html` – Login form posting to the `/login` endpoint
- `welcome.html` – Landing page after a successful login
- `server.js` – Express server integrating with Supabase
- `package.json` – Node.js dependencies

The project does not include Supabase credentials. You must supply them in your own `.env` file.
