//Album Tracker

This React app to search albums (iTunes Search API), preview tracks, keep a listening log with status, rating and notes, play full albums through Deezer's embeddable player,
and get LLM-powered recommendations (Google Gemini) based on your saved albums and ratings.

Live link: _add your Vercel URL here_
Screenshot: _add one here_

//Features
- Search albums and artists, 30-second previews, mini player that keeps playing while you browse
- Collection with status, 1-5 star rating, notes, filters and sorting (saved in your browser)
- Optional full-album playback with Deezer
- AI recommendations from your saved albums and ratings

//Tech stack
(React, Vite, Context API, iTunes API, Deezer, Gemini, Vercel)

//How to Run it locally
```bash
git clone https://github.com/Hainz34-Design/album-tracker.git
cd album-tracker
npm install
cp .env.local   //the Gemini api key
npm run dev
```

//Limitations
- Previews are 30 seconds (all iTunes provides)
- Collection is saved only in your browser
- Deezer needs a login (and a plan in your country) for full tracks

//Privacy
The recommendations feature sends your saved albums' titles, artists, ratings and statuses to Google's Gemini API. Notes are not sent.
