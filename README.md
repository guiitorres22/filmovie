<h1>Movie App Project</h1>
<p>This project is a <strong>React-based movie application</strong> that interacts with the <strong>TMDB API</strong> and an <strong>Appwrite backend</strong> to provide movie searching, trending movies, and search statistics functionalities.</p>

<h2>Features So Far</h2>
<ul>
  <li><strong>Movie Search:</strong> Users can search movies by keyword. The app fetches movie data from the TMDB API using a secure API key stored in environment variables.</li>
  <li><strong>Trending Movies:</strong> The app displays a list of trending/popular movies based on data stored and updated in the Appwrite database.</li>
  <li><strong>Search Analytics:</strong> When users search for movies, the app updates a count in Appwrite to track search term popularity.</li>
  <li><strong>Environment Variables:</strong> Secure keys and IDs for TMDB and Appwrite services are managed using Vercel environment variables.</li>
  <li><strong>Efficient API Calls:</strong> The app uses a debounce technique to limit frequent API requests during typing.</li>
  <li><strong>Modular React Components:</strong> The UI is split into reusable components such as Search, Spinner, MovieCard, and uses React hooks like useState and useEffect for state management.</li>
  <li><strong>Asset Handling:</strong> Images and icons are stored in the public folder and referenced properly to ensure availability in production.</li>
  <li><strong>Vite Build Setup:</strong> The project is set up with Vite for fast local development and optimized builds.</li>
  <li><strong>Deployment with Vercel:</strong> The app is deployed on Vercel with secure environment variable management and public hosting.</li>
</ul>

<h2>Technical Stack</h2>
<ul>
  <li>React (with hooks)</li>
  <li>Vite for build tooling</li>
  <li>TMDB API for movie data</li>
  <li>Appwrite for backend state persistence and search tracking</li>
  <li>Vercel for hosting and environment management</li>
</ul>

<h2>Next Steps</h2>
<ul>
  <li><input type="checkbox" disabled> Add functionality for filtering movies by country/language of origin on search.</li>
  <li><input type="checkbox" disabled> Improve UI and user experience with additional filters or features.</li>
  <li><input type="checkbox" disabled> Add movie summary
