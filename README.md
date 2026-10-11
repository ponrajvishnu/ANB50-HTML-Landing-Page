# Marquee: Cinema Ticket Booking Landing Page

A modern, fully responsive landing page for a cinema ticket booking platform, built with **pure HTML and CSS** in a single file. It uses no JavaScript and no frameworks.

## Features

- **Interactive seat map in the hero**: click seats to select them, with taken seats greyed out and a live "selected" counter, all done with CSS only
- **Now showing**: film poster cards with showtime chips
- **How it works**: a three-step booking flow (choose a film, pick seats, pay and go)
- **Screen formats**: Standard, IMAX and Recliner lounge with starting prices
- **Call to action and footer**: account sign-up prompt and site links
- **Fully responsive**: adapts to desktop, tablet and mobile
- **Accessible**: keyboard-navigable seat selection, visible focus states, and reduced-motion support

## Tech Stack

- HTML5
- CSS3 (custom properties, Grid, Flexbox, media queries)
- Google Fonts (Bricolage Grotesque, with system font fallbacks)

## Getting Started

1. Clone or download this repository.
2. Open `index.html` in any modern browser.

No build step or dependencies are required.

## Project Structure

```
.
└── index.html   # Markup and styles in one file
```

## Customization

- **Colors**: edit the CSS variables in the `:root` block at the top of the `<style>` section.
- **Films and showtimes**: update the `.film` cards in the "Now showing" section.
- **Seat layout**: add, remove or disable `<input type="checkbox">` seats inside the `.hall` block. A `disabled checked` seat shows as taken.
- **Pricing**: change the values in the `.fmt` cards.

## Notes

Film titles, prices and statistics are placeholder content. Replace them with real data before using this in production.

## License

This project is open source and available under the [MIT License](LICENSE).
