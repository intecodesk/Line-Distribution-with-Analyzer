Song Line Distribution Maker

A browser tool for tracking and visualizing who sings or raps how much in a song. Press a button while an artist is singing/rapping and a live bar race shows each artist's share, followed by a pie chart and a breakdown of the final percentages.

**[Live demo](YOUR-GITHUB-PAGES-LINK)**

## Features:
- Works for any song with 1–20 artists, whether a band, group, duet or choir
- Custom name and color for each artist
- Live bar race that reorders by singing time as the song plays
- Pie chart and a stats table with time (s) and percentage per artist
- Adjustable speed: you choose how many seconds the line takes to cross the screen
- Two layouts: `index.html` for phones, `laptop.html` for laptops, with automatic redirect
- Keyboard shortcuts on laptop: 1–9 and 0 for artists 1–10, Q–P for artists 11–20

## How to use:
1. Enter the number of artists and how many seconds the line should take to cross the screen.
2. Name each artist and pick a color.
3. Click **Generate Platform**.
4. Start the song. Press an artist's button (or key) when they start singing and press it again when they stop.
5. Click **Pie Chart →** to see the final distribution.

## Run locally
No build step or install needed. Download the repo and open `index.html` in a browser. An internet connection is needed for the pie chart (Chart.js is loaded from a CDN).

## Built with
HTML, CSS and vanilla JavaScript, plus [Chart.js](https://www.chartjs.org/) for the pie chart.
