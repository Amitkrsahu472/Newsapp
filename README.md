
# News website

A responsive and feature-rich news application built using React.js. This app fetches top headlines from various categories and displays them in an easy-to-navigate interface with infinite scrolling.

## Features

- **Category-Based News**: Browse news across multiple categories like Business, Entertainment, Health, Science, Sports, and Technology.
- **Infinite Scrolling**: Load more articles as you scroll down the page, providing a seamless experience.
- **Responsive Design**: Fully responsive and optimized for different devices.
- **Dynamic Navigation**: Easily switch between different news categories using the navigation bar.
- **Efficient State Management**: Minimized re-renders and optimized loading times through efficient state management.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/NewsApp.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd NewsApp
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Start the development server:**
   ```bash
   npm start
   ```
   The app will be available at `http://localhost:3000`.

## Usage

- **Homepage**: Displays top headlines from the selected country and category.
- **Navigation Bar**: Use the navigation bar to switch between different categories.
- **Infinite Scrolling**: Scroll down to load more articles from the selected category.

## Project Structure

- `src/`
  - `Components/`
    - `Navbar.js`: Contains the navigation bar.
    - `News.js`: Handles the main news feed with infinite scrolling.
    - `NewsItem.js`: Renders individual news articles.
    - `Spinner.js`: Displays a loading spinner during data fetching.
  - `App.js`: The root component where routes and navigation are defined.
  - `index.js`: Entry point for the React application.

## API Integration

This project integrates with the [NewsAPI](https://newsapi.org/) to fetch real-time news data. Make sure to replace the `apiKey` in the `News.js` component with your own API key from NewsAPI.

