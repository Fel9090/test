# Resubscribe App

A simple web app for managing newsletter resubscriptions using Google Sheets and Google Apps Script.

## 🚀 Features

- Users submit their name and email to resubscribe.
- Data is logged to the **Submission** sheet.
- Upon approval, entries are copied to **Resubscribe** and **Active** sheets.

## 🛠️ Setup

1. Clone this repo.
2. Open `apps-script.gs` in [Google Apps Script](https://script.google.com).
3. Deploy as a Web App with access set to **Anyone**.
4. Replace `proxyURL` in `index.html` with your Web App URL or Cloudflare Worker URL.
5. Host `index.html` on GitHub Pages, Vercel, or any static site host.

## 📊 Sheets Used

- [Submission](https://docs.google.com/spreadsheets/d/1FAzy0r8xzMcXmDxRvBY7dJ1XSGIke1Ty-oY4BQg9G1I/edit?gid=259591227)
- [Resubscribe](https://docs.google.com/spreadsheets/d/1FAzy0r8xzMcXmDxRvBY7dJ1XSGIke1Ty-oY4BQg9G1I/edit?gid=425919910)
- [Unsubscribe](https://docs.google.com/spreadsheets/d/1FAzy0r8xzMcXmDxRvBY7dJ1XSGIke1Ty-oY4BQg9G1I/edit?gid=1424557745)
- [Active](https://docs.google.com/spreadsheets/d/1FAzy0r8xzMcXmDxRvBY7dJ1XSGIke1Ty-oY4BQg9G1I/edit?gid=0)

## 🌐 Proxy Option

If you're facing CORS issues, you can use a Cloudflare Worker to proxy requests to your Apps Script endpoint.

## 📄 License

MIT
