# 3D Globe Visualization with Three.js

This repository contains a simple Three.js application that renders a 3D globe. It displays feature outlines on a sphere, surrounded by a starfield, and offers simple user interaction (orbit controls).

## Features

- **Interactive 3D Globe**: Rotate and zoom the globe using orbit controls.
- **Country Outlines**: Visualizes feature borders using GeoJSON data.
- **Starfield Background**: Enhances the visual experience with a starfield effect.

### Installation

1. **Clone the repository**

   ```bash
   git clone ttps://github.com/bobbyroe/3d-globe-with-threejs.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd 3d-globe-with-threejs
   ```

3. **Set up a local server**

   Install `live-server` globally:

   ```bash
   npm install -g live-server
   ```

   Or use it via `npx`:

   ```bash
   npx live-server --port=8080
   ```

4. **Run the server**

   ```bash
   live-server --port=8080
   ```

   This will serve the files in the current directory at `http://localhost:8080`.

5. **Open the application in your browser**

   Navigate to `http://localhost:8080` to view the globe visualization.


## Data Sources

- **GeoJSON Data**: Country outlines are sourced from [Natural Earth GeoJSON](https://github.com/martynafford/natural-earth-geojson).
- **Additional Datasets**: For more datasets, visit [Natural Earth Data](https://www.naturalearthdata.com/downloads/).

## License

This project is licensed under the MIT License.

## Acknowledgments

- **Three.js**: [threejs.org](https://threejs.org/)
- **Natural Earth Data**: [naturalearthdata.com](https://www.naturalearthdata.com/)