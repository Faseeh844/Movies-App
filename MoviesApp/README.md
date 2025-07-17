# Movies App

A React application for browsing, searching, and favoriting movies using [The Movie Database (TMDb) API](https://www.themoviedb.org/documentation/api). Built with [Vite](https://vitejs.dev/) for fast development and optimized builds.

## Features

- Browse popular movies on the home page
- Search for movies by title
- Mark/unmark movies as favorites (persisted in localStorage)
- View your list of favorite movies
- Responsive and modern UI

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/movies-app.git
   cd movies-app
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Configure API Key:**
   - Get a free API key from [TMDb](https://www.themoviedb.org/settings/api).
   - Replace `API_KEY_HERE` in `src/services/api.js` with your actual API key.

4. **Start the development server:**
   ```sh
   npm run dev
   # or
   yarn dev
   ```

   The app will be available at [http://localhost:5173](http://localhost:5173).

### Build for Production

```sh
npm run build
# or
yarn build
```

### Preview Production Build

```sh
npm run preview
# or
yarn preview
```

## Project Structure

```
MoviesApp/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── MovieCard.jsx
│   │   └── NavBar.jsx
│   ├── contexts/
│   │   └── movieContexts.jsx
│   ├── css/
│   ├── pages/
│   │   ├── Favorites.jsx
│   │   └── Home.jsx
│   ├── services/
│   │   └── api.js
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── package.json
└── ...
```

## Customization

- Update styles in the `src/css/` directory.
- Modify components in `src/components/` and pages in `src/pages/`.
- Extend context logic in `movieContexts.jsx` as needed.

## License

This project is for educational/demo purposes.

---

**Note:** This app uses the TMDb API but is not endorsed or certified by