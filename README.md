# Movix

## 1. Project Description
Movix is a movie and TV show information web application built using **React + Vite**.  
It fetches data from an external movie database API (such as TMDB) and displays trending, popular, and top-rated content with an intuitive and responsive UI.  

The project provides features like:
- Browse trending movies and shows
- Search by title
- View detailed information (overview, ratings, release date, etc.)
- Responsive design for both desktop and mobile

---

## 2. Setup & Running Locally

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn
- An API key from [The Movie Database (TMDB)](https://www.themoviedb.org/) or another supported movie API

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shashank-jha22/movix.git
   cd movix
Install dependencies

npm install


Or with yarn:

yarn install


Set environment variables
Create a .env file in the root directory and add your TMDB API key:

VITE_TMDB_API_KEY=your_tmdb_api_key_here


Run development server

npm run dev


This will start a local server (usually at http://localhost:5173).

Build for production

npm run build


Preview production build

npm run serve

⚙️ Assumptions & Design Choices

API Source → Uses TMDB API for fetching data.

Environment Variables → API keys are stored in .env (not hard-coded).

Frontend Only → No backend; all data fetched directly from TMDB.

Responsive UI → Works across desktop, tablet, and mobile.

Error Handling → Handles invalid API keys and network issues gracefully.

State Management → Implemented using React hooks/context (lightweight approach).

No Tests Yet → Assumed tests will be added in future updates.

📌 Future Enhancements

Add automated test cases

Implement favorites/watchlist feature

Enhance error messages and offline mode

Cache API responses for better performance

Add authentication for personalized experience

📷 Screenshots (Optional)

Add screenshots of your app UI here for better presentation.

🛠️ Tech Stack

React (with Vite for fast build & HMR)

TMDB API

CSS/SCSS / Tailwind (if used)

React Router (for navigation)
