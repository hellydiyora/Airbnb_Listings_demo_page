# Airbnb Listings Assignment

This project implements a responsive Airbnb listings page using vanilla JavaScript, HTML, and CSS. It fetches 50 listings from a local JSON dataset and displays them with a clean, modern card layout.

## Features

-   **Data Fetching**: Loads listing data asynchronously using `fetch` and `await`.
-   **Dynamic Rendering**: Parses JSON data (including stringified amenities) to display:
    -   Listing Name
    -   Host Name & Photo
    -   Price
    -   Thumbnail Image
    -   Ratings
    -   Amenities preview
-   **Creative Addition: Favorites System**:
    -   Users can click the "Heart" icon on any listing to add it to a "Favorites" sidebar.
    -   Favorites are persisted using `localStorage`, so they remain after refreshing the page.
    -   Users can remove items directly from the sidebar.

## Setup

1.  Clone this repository.
2.  Open `index.html` in your web browser.
3.  Ensure `airbnb_listings2/airbnb_sf_listings_500.json` exists in the directory.

## How to View

### Option 1: Live Demo (Recommended)
View the deployed version on GitHub Pages here:
**[Link to Deployment](https://helly.github.io/Airbnb_Listings_Assignment)**
*(Note: No installation required)*

### Option 2: Local Development
If you want to run this code on your own computer, you cannot simply open `index.html` due to browser security (CORS) preventing JSON loading. You must use a local server.

**Recommended:**
-   Use **VS Code**: Install "Live Server" extension -> Click "Go Live".
-   Or any other local server you prefer.

## License

MIT
# Airbnb_Listings_demo_page
