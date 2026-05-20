# cinema-finder
🎬 Cinema Finder POC  A simple cinema finder web application built with React. Users can browse cinema locations, nearby cinemas, and franchise-based cinema listings with an interactive map interface.
🚀 Live Demo
Cinema Finder Demo

🛠️ Tech Stack
1. React
2. React Router
3. Material UI (MUI)
4. Leaflet / Map Integration
5. Dynamic Imports
6. Code Splitting
7. Netlify Deployment

✨ Features
1. Interactive cinema map
2. Nearby cinema search
3. Franchise filtering
4. Dynamic routing
5. Responsive layout
6. Lazy loading components for better performance

🔧 Example Bug Fix
One major issue in this project was React Router compatibility.

Old Code
<Switch>
  <Route path="/" component={Home} />
</Switch>

Fixed Code
<Routes>
  <Route path="/" element={<Home />} />
</Routes>

Why?
React Router v6 removed Switch and replaced it with Routes.
This fix prevents routing crashes and blank screens.

📦 Installation
yarn install
yarn start

🌐 Deployment
Deployed with:
Netlify

Author
Darwin Surya Pangestu
https://www.linkedin.com/feed/
