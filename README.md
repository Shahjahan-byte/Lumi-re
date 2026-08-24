🎬 Lumière — Cinematic Streaming Experience
Lumière Banner

A modern, out-of-the-box 3D movie streaming web application.
Featuring a macOS-inspired glassmorphic UI, WebGL particle backgrounds, and a massive library of Hollywood, Bollywood, Korean, Japanese, and European cinema.

StatusMoviesLanguagesSources

✨ Features
🎨 Design & UI/UX
macOS-Inspired Interface: Frosted glass top bar with functional traffic lights, magnifying Dock at the bottom, and window-style player modals.
WebGL Background: A custom Three.js particle nebula with 4,000 colored particles and floating wireframe crystal shards that react to mouse parallax.
3D Tilt Movie Cards: Every film features a perspective-tilt on hover, complete with a cursor-tracking spotlight effect and glowing borders.
Glassmorphism: Heavy use of backdrop-filter: blur() and saturate for true frosted-glass aesthetics.
Cinematic Hero Section: Auto-rotating featured carousel with 3D tilting posters, dynamic background blurring, and glowing ambient effects.
🍿 Content & Library
60+ Worldwide Movies: Hand-curated selection spanning Hollywood, Bollywood, Korean, Japanese, Spanish, French, Italian, and German cinema.
Genres Galore: Includes Sci-Fi, Horror, Comedy, Animation, Crime, Thriller, Drama, and more.
Dual Filtering System: Combine Genre pills (Sci-Fi, Horror, etc.) with Language pills (English, Hindi, Korean, etc.) simultaneously.
Shuffle Feature: "Surprise Me" button to instantly play a random film from the current filter pool.
📺 Streaming & Player
10 Streaming Sources: Embeds via Cinezo (Primary), VidSrc, 2Embed, Embed.su, SmashyStream, Embedsito, and MultiEmbed.
TMDB & IMDb Support: Fallback system uses both TMDB IDs and IMDb IDs to ensure maximum compatibility across different embed APIs.
Loading States: Elegant loading spinner inside the player modal while establishing secure streams.
Persistent Watchlist: "My List" functionality saves to localStorage, allowing users to bookmark films across sessions.
⚡ Functionality
⌘K / Ctrl+K Search: Instant search by title, genre, language, or year.
Intersection Observer: Smooth reveal animations as you scroll down the page.
Fully Responsive: Adapts beautifully from ultra-wide desktops down to mobile devices.
🛠 Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6+)
3D/WebGL: Three.js (via ES Modules import map)
Styling: Tailwind CSS (CDN), custom CSS variables.
Fonts: Outfit & JetBrains Mono.
Icons: Font Awesome 6.5.1.
Metadata/Images: TMDB (The Movie Database) image CDN.
