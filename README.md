# ressource-manager

A lightweight, web-based tool for managing organizational resources, tracking FTE (Full-Time Equivalent) distribution, and monitoring vendor allocation.

## 🚀 Features

- **Dashboard Analytics:** Real-time stats on Section FTEs, Status distribution, and Vendor counts.
- **Resource Tracking:** Manage resources across four customizable sections.
- **Capacity Alerts:** Visual warnings for FTE conflicts (over 1.0 FTE) and "High Load" status.
- **Filtering:** Quickly filter by active status, high-load resources, or external vendors only.
- **Data Portability:** Export data to CSV or generate a updated `data.js` file for persistence.

## 🛠️ Tech Stack

- **Frontend:** Pure HTML5, CSS3 (Modern Flexbox/Grid), and Vanilla JavaScript.
- **Data Persistence:** LocalStorage for browser-side saving and `data.js` for hard-coded source data.

## 📖 Quick Start Guide

### Local Development
1. Open your terminal in the project folder.
2. Run `open index.html` (Mac) or use any browser etc. 
3. The app will automatically load data from `data.js`.

### Updating Data
To update the data source permanently:
1. Use the **Add New** button in the app to modify your list.
2. Click **Download data.js** in the top menu.
3. Copy the generated code and replace the content inside your `data.js` file.
4. Commit and Push to GitHub to update the live version.

## 🔒 Security & Privacy

This project is designed with anonymity in mind - you can change all values, so they fit your project:
- **Vendors** are labeled as "Vendor 1, 2, 3, etc."
- **Internal Staff** are labeled as "Internal".
- **Sections** are categorized as "Section 1, 2, 3, 4".

*Note: If hosting on GitHub Pages, ensure no sensitive personal data is included in your `data.js` file.*

## 📄 License
MIT License - Feel free to use and modify for your own organizational needs.
