# ini website guwe

A movie discovery site powered by the TMDB API. Features movie info, ratings, reviews, genres, and YouTube trailers.

## Deploy on Vercel

1. Push this project to a Git repository (GitHub, GitLab, or Bitbucket).
2. Go to [vercel.com](https://vercel.com) and sign in.
3. Click **Add New** → **Project** and import your repository.
4. Leave **Build Command** and **Output Directory** empty (static site).
5. Click **Deploy**.

### URLs after deploy

- **Home:** `https://your-project.vercel.app/`
- **Movies:** `https://your-project.vercel.app/movies`

### TMDB API

The site uses a TMDB Bearer token in the front end. For production you may want to hide it behind a serverless API route. Update `TMDB_OPTIONS` in `movie.html` and `movies.html` if you change the token.
