# Canada - School Project

A small, static website introducing Canada. It was created as a school presentation and guides visitors through a sequence of pages about the country, its flag, anthems, and geography.

(Don't forget to check my page for more projects!)

## Contents

The site follows this navigation:

1. **Home** (`index.html`) - project title and a button to begin.
2. **About Canada** (`aboutcanada.html`) - an overview of Canada's location, size, coastline, provinces and territories, and population.
3. **Canada's Flag** (`flaginfo.html`) - the flag's design, history, and symbolism.
4. **Anthems** (`anthems.html`) - audio players for "O Canada" and the royal anthem, along with Canada's motto.
5. **Geographical Information** (`geoinfo.html`) - a selection of country facts and a map showing Canada's location.
6. **Thanks** (`thanks.html`) - closing page with a link to the resource list in `resources.md`.

Each presentation page has a **GO** button that advances to the next page. Use the browser's Back button to return to a previous page.

## Run the project

There is no build step, package installation, or framework required. Open `index.html` in a modern web browser to view the presentation.

For local development, you can also serve the project directory with any static HTTP server and open its `index.html` page. Keep the files together: pages refer to stylesheets, images, and audio using paths relative to the project directory.

An internet connection is needed to load the externally hosted map image and Google Fonts. The local pages and bundled audio do not require a backend.

## Project files

| File | Purpose |
| --- | --- |
| `index.html` | Landing page and entry point |
| `aboutcanada.html` | Introductory information about Canada |
| `flaginfo.html` | Flag image and description |
| `anthems.html` | Anthem descriptions and audio players |
| `geoinfo.html` | Geography and country facts |
| `thanks.html` | Closing page and resource link |
| `style.css` | Landing-page styles |
| `styleslide1.css` | Styles for the "About Canada" page |
| `styleslide2.css` | Styles for the flag page |
| `anthems.css` | Styles for the anthems page |
| `entrance.jpg` | Landing-page background image |
| `canada_flag.webp` | Flag image used on the flag page |
| `O_Canada.oga` | "O Canada" audio |
| `Royal_anthem_Canada.ogg` | Royal anthem audio |
| `resources.md` | Information and media source links |
| `index.js` | Empty placeholder; no JavaScript file is currently needed by the pages |

The geography page includes its styles inline and loads its map from Wikimedia Commons. Some pages also load fonts from Google Fonts.

## Sources and media

The project's source links and media references are collected in [`resources.md`](resources.md). They include references to Wikipedia, Geodatos, Tripadvisor, and Wikimedia Commons. The map is loaded from Wikimedia Commons at runtime; the cover and flag image files are included in the project directory.

## Notes

- Country statistics and office-holder names are written directly into the HTML, so they are fixed snapshots rather than live data. Review them against current sources before reusing the presentation.
- This is a static educational project; it has no server-side code, database, or automated test suite.
