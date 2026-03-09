# CNTC 2026 Website

A modern conference website built for **CNTC 2026** using **React**, **Vite**, and **Tailwind CSS**.

This project was designed as a clean, responsive event site featuring core conference pages such as speakers, schedule, sponsors, and general event information.

## Overview

The site includes:

- A landing page for conference highlights
- Speaker and panelist pages
- Event schedule and program information
- Sponsor and partner showcases
- About page and organization details
- Client-side routing for a smooth multi-page experience

## Tech Stack

- **React**
- **Vite**
- **React Router**
- **Tailwind CSS**
- **lucide-react**

## Features

- Responsive layout across desktop and mobile
- Reusable component structure
- Static content managed through organized data files
- Fast frontend performance with Vite
- Clean routing for multiple public-facing pages

## Project Structure

```text
src/
  components/
    Navbar.jsx
  pages/
    Home.jsx
    About.jsx
    Events.jsx
    Speakers.jsx
    Sponsors.jsx
    NotFound.jsx
  data/
    homeData.js
    aboutData.js
    eventsData.js
    speakerData.js
  assets/
  lib/
  App.jsx
  main.jsx
  index.css
```

## Getting Started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## Notes

This project emphasizes:

- Frontend architecture for a real-world event site
- Maintainable page and component organization
- Scalable static content management
- Polished UI for a public-facing conference experience

## License

This project is for portfolio and educational use unless otherwise specified.