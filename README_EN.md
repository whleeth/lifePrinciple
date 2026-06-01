# CORE VALUES - Life Principle Selector

An interactive single-page website that helps users rank their life values through pairwise choices powered by an `Elo Rating`-style system. After a series of decisions, the app generates a personal "core values structure report."

## Demo

- Live Demo: [Open the site](https://whleeth.github.io/lifePrinciple/)

## Screenshot

![Select](./assets/select.png)
![Reminder](./assets/reminder.png)
![Reset](./assets/reset.png)
![Current T1 T2](./assets/current-t1-t2.jpg)
![Current T2 T3](./assets/current-t2-t3.png)
![Copy Resume](./assets/copy-resume.jpg)
![Final 12](./assets/final-12.jpg)
![Final Report](./assets/final-report.jpg)
![Final T1B3](./assets/final-t1b3.jpg)

## Features

- Pairwise comparisons for quickly identifying priority values
- Built-in `Elo` ranking system that updates after each choice
- Supports mouse clicks, keyboard left/right arrows, and mobile swipe gestures
- Undo the previous choice, reset the data, generate a report, and copy report text
- Dark-themed card UI optimized for both desktop and mobile

## Sections

- `CORE VALUES` main stage for value duels
- `Undo` to revert the last choice
- `Reset` to clear all ranking data
- `Generate Report` to build the final result summary
- `Copy Report` to copy the text report to clipboard
- `Resume Duel` to return to the comparison flow

## Usage

1. Open `index.html` in a browser
2. Choose the value that matters more to you in each pair
3. Continue until you are ready to generate the report
4. Copy the report text or share the results as needed

## Tech Stack

- HTML5
- Tailwind CSS via CDN
- Vanilla JavaScript
- Google Fonts

## Notes

- This is a single-file static page with no `package.json` or frontend framework dependencies
