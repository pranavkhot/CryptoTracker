# Crypto Tracker 🚀

**Crypto Tracker** is a modern web application developed with [Next.js](https://nextjs.org/) and [React](https://reactjs.org/) that enables users to monitor real-time cryptocurrency data. Users can easily access essential information, such as current prices, market cap, and volume, in an intuitive and visually appealing interface. The app’s clean, responsive design provides a seamless experience across devices.

---
<p align="center">
  <a href="https://cryptotracker-pi.vercel.app" target="_blank">
    <img src="https://github.com/user-attachments/assets/b748141c-11a3-49c0-943d-a7d1a3b41cb1" alt="Crypto Tracker Website"/>
  </a>
</p>

---


## 📜 Table of Contents
- Features
- Tech Stack
- Usage
- Project Structure

---
## ✨ Features

- **📈 Real-time Cryptocurrency Tracking**: View updated cryptocurrency data, including prices, volume, market cap, and percentage changes.
- **🔍 Search Functionality**: Quickly find specific cryptocurrencies using a convenient search bar.
- **🔗 Detailed Coin View**: Access individual cryptocurrency details, such as an image, ticker, and current price, on a dedicated page.
- **🌙 Dark-Themed UI**: Consistent, dark theme provides a polished user experience that is easy on the eyes.
- **📱 Responsive Design**: Fully responsive layout ensures accessibility across devices of various screen sizes.

---

## 🛠️ Tech Stack

- **Frontend**:
  - **Next.js**: Used for server-side rendering, routing, and optimized static site generation.
  - **React**: Provides a component-based structure for building the user interface.
- **Styling**:
  - **CSS Modules**: Component-specific CSS files provide scoped styling for each part of the UI.
  - **Global CSS**: Common styles for the overall layout and appearance of the application.
- **Deployment**:
  - **Netlify**: Enables fast and scalable deployment, optimized for static and serverless applications.

---

## 🚀 Usage

When running the application:

1. **Home Page**: Access a list of popular cryptocurrencies with live updates for easy monitoring.
2. **Search**: Use the search bar to quickly locate any cryptocurrency by name or ticker symbol.
3. **Details Page**: Click on a cryptocurrency for more in-depth information, including its image, ticker, and real-time price.

---

## 📁 Project Structure

A quick look at the core files and their responsibilities:

- **public/**: 
  - Contains static assets such as icons, images, and other resources required across the application.

- **pages/**:
  - `index.js`: Main page listing the popular cryptocurrencies with essential data such as price, volume, and percentage changes. 
  - `[id].js`: A dynamic routing page that generates individual detail views for each cryptocurrency, including a larger display of the coin’s image, ticker symbol, and current price.

- **components/**:
  - `Layout.js`: Handles the layout structure shared across the application, including consistent styling and reusable components like headers and footers.
  - `CoinList.js`: Renders the list of cryptocurrencies, applying relevant styles and presenting essential metrics for each coin in a visually structured manner.

- **styles/**:
  - `globals.css`: Defines global styles, including fonts, colors, and universal styling defaults such as box-sizing, margin, and padding, with an imported font for consistency.
  - `Coins.module.css`: Styles specifically for the main cryptocurrency list view, including hover effects, row structure, and color-coded price change indicators.
  - `Coin.module.css`: Styles the detailed view for individual cryptocurrencies, centering content and emphasizing elements such as the coin’s name, ticker, and price.
  - `Search.module.css`: Provides custom styling for the search bar, including a dark background and a modern input placeholder color for easy readability.

- **package.json**: Defines the project’s metadata, scripts, and dependencies (like Next.js and React) that power the application.


---

**Enjoy tracking with Crypto Tracker! 💰🚀**
