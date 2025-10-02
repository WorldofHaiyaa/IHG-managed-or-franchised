# IHG Properties Interactive Map

An interactive web map designed to visualize the global distribution of properties under the InterContinental Hotels Group (IHG), built with Leaflet.js.

<img width="2352" height="935" alt="image" src="https://github.com/user-attachments/assets/5cb46807-7c31-4160-8c18-cb2b8da18138" />

## ✨ Features

- **Interactive Map**: Built with Leaflet.js for a smooth panning and zooming experience.
- **Data Visualization**:
    - **Color-Coded Markers**: Properties are color-coded by management type:
        - ![#4b77a9](https://placehold.co/15x15/4b77a9/4b77a9.png) **Managed**
        - ![#add8e6](https://placehold.co/15x15/add8e6/add8e6.png) **Franchised**
        - ![#800080](https://placehold.co/15x15/800080/800080.png) **(Partially) Owned**
        - ![#808080](https://placehold.co/15x15/808080/808080.png) **Unknown**
    - **Dynamic Opacity**: Marker opacity changes based on the hotel's opening year—older properties are more transparent.
- **Popups**: Clicking on a marker reveals hotel details, including its name, management type, opening date, and a link to its official page.
- **Geolocation & Search**:
    - **Search Bar**: Instantly fly to any city, place, or country on the map.
    - **My Location**: A button to center the map on your current location.
    - 
## 🛠️ Powered by

- **Map Library**: [Leaflet.js](https://leafletjs.com/)
- **Basemap Tiles**: [CartoDB](https://carto.com/)

## 📄 License

This project is licensed under the [MIT License](LICENSE).
