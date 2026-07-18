# Kasatria - Candidate Periodic Table

Interactive 3D visualization of 200 candidates built as part of the Kasatria Software Developer preliminary assignment.

## Overview

A single-page application that visualizes candidate data in four different 3D layouts using Three.js CSS3DRenderer. Data is fetched live from a Google Sheet and color-coded by net worth.

## Features

- Google Sign-In authentication
- Live data fetching from Google Sheets
- Four interactive layouts:
  - Table (20×10)
  - Sphere
  - Double Helix
  - Grid (5×4×10)
- Color coding based on Net Worth
- Responsive controls (drag to rotate, scroll to zoom)

## Tech Stack

- Three.js (r128) + CSS3DRenderer
- Google Identity Services
- Google Sheets (public gviz endpoint)
- Vanilla JavaScript

## Live Demo

(https://kasatria-candidate-periodic-table.vercel.app/)

## Setup

1. Clone the repository
2. Open `index.html` in a local server (Live Server / Python HTTP server)
3. Update `CONFIG` object with your Google Client ID and Sheet ID if needed

## Notes

- Google Sheet must be shared as "Anyone with the link can view"
- Google OAuth Client ID must have the correct authorized JavaScript origins
