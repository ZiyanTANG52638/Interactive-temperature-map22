# Interactive Temperature Map

This project is an **interactive temperature map** built with HTML, JavaScript, and Leaflet.js. It allows users to upload temperature data, add location markers, and display related photos on a map.

---

## Features
- **Interactive Map**: Uses Leaflet.js and Mapbox for map visualization.
- **User Input**: Users can add a nickname, latitude, longitude, temperature, and a photo.
- **Dynamic Marker**: Displays the uploaded information as a map marker with a popup.

---

## Getting Started

Follow these steps to run the project locally.

### Prerequisites
1. Install a simple local server (e.g., Python's HTTP server, VSCode Live Server, etc.).
2. Clone the repository.

---

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/interactive-temperature-map.git
2. **Navigate to the project directory**:
   ```bash
   cd interactive-temperature-map
3. **Start a local server**:
   Using Python (Example):
   ```bash
   python -m http.server
By default, the server runs on http://localhost:8000.

Using VSCode Live Server:
- Open the project folder in Visual Studio Code.
- Install the Live Server extension.
- Right-click on the index.html file and select Open with Live Server.

4. **Open the project in your browser:**:
- For Python, navigate to http://localhost:8000 in your web browser.
- For VSCode Live Server, the browser will open automatically.


## Usage
1. **Fill out the form:**:
- Nickname (e.g., John Doe).
- Latitude (e.g., 24.5).
- Longitude (e.g., 117.5).
- Temperature (e.g., 25°C).
- Upload a photo.

2. **Add data to the map:**
- Click the Add Data to Map button.
- A new marker will be added to the map at the specified location.
- The popup will display the uploaded data and the photo.

3. **View markers:**
- The map view will automatically adjust to include all markers.

4. **Reset the form:**
- The form will clear automatically after submission.

## Project Structure
The project files are organized as follows:
- index.html: The main HTML file containing the form, map, and JavaScript logic.
- README.md: The documentation file you are currently reading.

## Technologies Used
- HTML5: Markup for the web page structure.
- CSS3: Styling for the map and UI elements.
- JavaScript (ES6): Logic for user input, map interaction, and marker updates.
- Leaflet.js: Open-source JavaScript library for map visualizations.
- Mapbox: Satellite imagery and tiles for the map.

## Features Overview
Map Features:
- Satellite imagery provided by Mapbox.
- Dynamic zooming based on marker locations.
- Interactive popups displaying user-submitted data.
Form Features:
- Input validation for latitude, longitude, and temperature.
- Support for uploading and displaying images in popups.

## How to Extend the Project
1. Back-End Integration:
   - Connect the form submission to a back-end service using Node.js and Express.
   - Store user submissions (nickname, latitude, longitude, temperature, and photo) in a MongoDB database.
3. Enhanced Map Features:
   - Add clustering for markers to improve map readability with multiple submissions.
   - Display additional weather data using a weather API (e.g., OpenWeatherMap).
5. User Authentication:
   - Add login functionality to allow users to save and manage their submissions.
  
## Contributing
If you'd like to contribute to this project:
1. Fork the repository.
   - Create a copy of the repository under your GitHub account.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
3. Commit your changes:
   ```bash
   git commit -m 'Add feature name'.
4. Push to your branch:
   ```bash
   git push origin feature-name.
5. Open a pull request.
   - Provide a detailed description of the changes you made.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- [Leaflet.js Documentation](https://sl7j8l.aitianhu2.top/c/676676e3-fb74-800c-bbb4-b951a1f9be25)
- [Mapbox Documentation](https://sl7j8l.aitianhu2.top/c/676676e3-fb74-800c-bbb4-b951a1f9be25)
