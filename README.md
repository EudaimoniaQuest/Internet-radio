# Radio Station Picker 🎧

A lightweight, browser-based interface for discovering and streaming curated radio stations by genre and artist.

## Features

- 🎵 **Genre Browsing** – Browse artists by predefined categories like Rock, Pop, Jazz, Classical, and more.
- 🔍 **Search** – Instantly search for any artist across all genres.
- 🎲 **Random Pick** – Get a random artist from the current genre.
- ⭐ **Favourites** – Save and revisit your favourite stations (stored locally).
- 📜 **Listening Log** – Keep a session-based log of played artists with copy/export options.
- 🌓 **Dark UI** – Clean, dark-themed interface ideal for low-light environments.
- 📱 **Mobile Friendly** – Designed to work well in iOS web views and modern mobile browsers.

## Usage

1. **Download or clone the repo.**
2. Open `index.html` in any modern browser.
3. Click a genre, pick an artist, and start listening.

## File Structure

- `index.html` – Main interactive interface.
- `genreData.js` – JSON-style object with genres and artists (customisable).
- `style.css` – Dark-themed styling.
- `script.js` – Core logic for search, selection, and local storage.

## Customisation

You can add, remove, or modify genres and artists by editing the `genreData` object in your JavaScript. Each entry requires a `name` and a `url` (streaming link).

Example:
```js
"Rock": [
  { "name": "Foo Fighters", "url": "http://streaming.exclusive.radio/er/foofighters/icecast.audio" }
]
