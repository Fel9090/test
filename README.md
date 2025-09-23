# Resubscribe App

A simple web app for managing newsletter resubscriptions using Google Sheets and Google Apps Script.

## Features

- Users submit their name and email to resubscribe.
- Data is logged to the "Submission" sheet.
- Upon approval, entries are copied to "Resubscribe" and "Active" sheets.

## Setup

1. Clone this repo.
2. Open `apps-script.gs` in Google Apps Script.
3. Deploy as a Web App (access: Anyone).
4. Replace `proxyURL` in `index.html` with your Web App URL.
5. Host `index.html` on GitHub Pages or any static site host.

## Sheets Used

- [Submission](https://docs.google.com/spreadsheets/d/1FAzy0r8xzMcXmDxRvBY7dJ1XSGIke1Ty-oY4BQg9G1I/edit?gid=259591227)
- [Resubscribe](https://docs.google.com/spreadsheets/d/1FAzy0r8xzMcXmDxRvBY7dJ1XSGIke1Ty-oY4BQg9G1I/edit?gid=425919910)
- [Unsubscribe](https://docs.google.com/spreadsheets/d/1FAzy0r8xzMcXmDxRvBY7dJ1XSGIke1Ty-oY4BQg9G1I/edit?gid=1424557745)
- [Active](https://docs.google.com/spreadsheets/d/1FAzy0r8xzMcXmDxRvBY7dJ1XSGIke1Ty-oY4BQg9G1I/edit?gid=0)

## License

MIT
