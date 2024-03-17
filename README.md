# NavNexus

NavNexus is a simple web application that allows users to search for locations and view them on a map. Once a location is typed into the search bar, NavNexus lists the available places, and upon clicking on a place, it marks a corresponding marker on the map.

![navnexus](https://i.imgur.com/Dbfjc0p.png)

## Features

- **Location Search**: Users can type in a location in the search bar, and NavNexus will display a list of available places matching the search query.
- **Interactive Map**: The application provides an interactive map interface powered by Leaflet, allowing users to visualize selected locations.

## Getting Started

To run NavNexus locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/colson0x1/navnexus.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:5173` to view the application.

## Usage

1. Upon loading the application, you will see a search bar on the left side and an interactive map on the right side.
2. Type the desired location into the search bar.
3. NavNexus will display a list of available places matching the search query.
4. Click on a place from the list to mark its location on the map.
5. Explore different locations by repeating the search and selection process.

## Code Structure

- **`src/App.tsx`**: The main component of the application that renders the search bar and the map.
- **`src/components/LocationSearch.tsx`**: Component responsible for handling location search functionality and displaying search results.
- **`src/components/Map.tsx`**: Component that renders the interactive map using Leaflet and displays markers for selected locations.
- **`src/api/Place.ts`**: Defines the structure of a Place object.
- **`src/api/search.ts`**: Contains the function to perform location searches using the Nominatim API.

## Technologies Used

- **React**: Frontend framework for building user interfaces.
- **Leaflet**: An open-source JavaScript library for interactive maps.
- **Nominatim API**: OpenStreetMap's search engine for geocoding and reverse geocoding.

---

## Screenshots

**NavNexus** - Navigate the world with ease!

![navnexus](https://i.imgur.com/1R7ung1.png)

![navnexus](https://i.imgur.com/BludpnD.png)

![navnexus](https://i.imgur.com/j1QFhLp.png)

![navnexus](https://i.imgur.com/Dbfjc0p.png)
