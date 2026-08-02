# Australian Property Price Leaderboard - Real Estate Price Leaderboard 2026

> **A browser-based ranking tool for comparing residential asking prices across eight Australian capital cities, with searchable listings, sorting controls, and property filters.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/evanyoungrg9273/au-property-price-leaderboard?style=flat-square)](https://github.com/evanyoungrg9273/au-property-price-leaderboard)

---

<p align="center">
  <a href="https://evanyoungrg9273.github.io/au-property-price-leaderboard/">
    <img src="https://img.shields.io/badge/Download-Australian%20Property%20Price%20Leaderboard%20Latest-brightgreen?style=for-the-badge" alt="Download Australian Property Price Leaderboard">
  </a>
</p>

> **[Download Australian Property Price Leaderboard](https://evanyoungrg9273.github.io/au-property-price-leaderboard/)**

---

[Download Latest Build](https://evanyoungrg9273.github.io/au-property-price-leaderboard/)

---

## Explore Australian Property Prices

Australian Property Price Leaderboard is a static web application that presents residential home listings from eight Australian capital cities in a comparable ranking. Users can order results by total asking price, estimated price per square metre, or bedroom count.

Built for straightforward property research, the interface combines city and property-type filters with suburb search, summary cards, and visual price bars. Buyers, analysts, researchers, and anyone reviewing Australian real estate listings can browse the dataset without setting up a build system or complex application environment.

---

## What It Includes

- Compare residential listings from eight Australian capital cities
- Reorder results using asking price, price per square metre, or bedrooms
- Narrow the dataset by city or property type
- Find listings using suburb names
- Use calculated midpoint values to interpret asking-price ranges
- See key summary figures in compact overview cards
- Compare rows visually with individual price bars
- Run the project as a single HTML file containing the listing data
- Use vanilla JavaScript with no build step

---

## Getting Started

First, download the repository and enter its directory:

```bash
git clone https://github.com/evanyoungrg9273/au-property-price-leaderboard.git
cd REPO
```

The static application can then be launched directly from the HTML file:

```bash
open index.html
```

Windows users can double-click `index.html`, or run:

```powershell
start index.html
```

Alternatively, deploy the repository with GitHub Pages and visit the site at its project URL.

---

## Using the Leaderboard

1. Launch the application in a modern web browser.
2. Select a capital city to limit the visible results.
3. Choose a property type if you want to focus on a particular category.
4. Enter a suburb in the search field.
5. Select a ranking option for asking price, price per square metre, or bedrooms.
6. Consult the summary cards and row-level price bars while reviewing the results.
7. Refer to midpoint values for listings shown with a price range.

All listing data is embedded in the application and processed in the browser. Normal operation therefore does not require a separate server.

---

## Project Configuration

This project is structured as a single-file HTML application. The listing data and browser-side logic are included in the application files, and the user interface is powered by vanilla JavaScript.

To change the listings or modify how they are presented, update the embedded data and application logic in the HTML source. The project does not require package installation, a dependency manager, or compilation.

---

## Requirements

- A current web browser
- The static HTML file or access to a GitHub Pages deployment
- No server runtime for local use
- No build tools or package installation
- Repository storage for the project HTML and its embedded listing data

---

## Frequently Asked Questions

### What is the leaderboard designed for?

The project helps buyers, analysts, researchers, and other users compare Australian residential listings and examine asking-price patterns.

### Which cities appear in the data?

The leaderboard covers residential listings from eight Australian capital cities.

### Is suburb lookup supported?

Yes. Enter a suburb in the search field to reduce the list to matching homes.

### How does the application handle price ranges?

For listings with a price range, the application calculates the midpoint and uses that value for ranking and comparisons.

### What sorting choices are available?

You can arrange listings by asking price, price per square metre, or number of bedrooms.

### Do I need to run a build command?

No. The project is a static, single-file HTML application written with vanilla JavaScript. Open it directly in a browser or host it through GitHub Pages.

### What can I check if the page fails to load?

Make sure the HTML file was downloaded fully, open it with a current browser, and verify that the project files are still in their expected locations. If the problem remains, inspect the browser developer console for loading errors.

### How are new updates delivered?

Modify the application data or source files, then redeploy the static site through the repository's hosting workflow.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
