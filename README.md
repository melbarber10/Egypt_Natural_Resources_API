# Natural Resources of Egypt

A static website showcasing the rich and diverse natural resources of Egypt, with a strong focus on geospatial data. The site features an interactive map powered by the [ArcGIS JavaScript API](https://developers.arcgis.com/javascript/) that allows users to explore and visualize Egypt’s natural resources.

## Features

- **Home Page:** An introduction to Egypt's natural resources with detailed information.
- **About Page:** Background and context about the project.
- **Key Resources:** In-depth descriptions of Egypt’s natural assets including:
  - Minerals (gold, copper, granite, etc.)
  - Agricultural Land and Crop Diversity
  - Wastewater Treatment Plants
  - Egyptian Oases
  - Natural Protectorates
  - Tree Pruning Practices
  - Water Areas and the Nile River
- **Gallery:** A visual collection of images depicting Egypt's landscapes and resources.
- **Interactive Map:** An ArcGIS-powered map (accessible via `map.html`) that visualizes the geospatial distribution of Egypt's natural resources.
- **Contact:** Information for inquiries and further engagement.

## Technologies Used

- **HTML5** and **CSS3**
- **JavaScript**
- **ArcGIS JavaScript API** for interactive mapping
- **Font Awesome** for icons
- GIS concepts for spatial data visualization

## Project Structure

```
.
├── index.html          # Main landing page with information about Egypt's natural resources
├── map.html            # Page containing the ArcGIS-powered interactive map
├── styles.css          # CSS stylesheet for the website
├── images/             # Folder containing images used on the website
├── Presentation.pdf    # Presentation 2024
└── README.md           # README Documentation
```

## How to Run

### Option 1: Open Locally
1. **Clone or Download the Repository:**  
   Download the project files to your local machine.

2. **Open the Website:**  
   Open `index.html` in your web browser to view the site.  
   Click the "Map" link or open `map.html` directly to view the ArcGIS-powered interactive map.

### Option 2: Serve via a Local Web Server (Optional)
For an improved experience (especially if using interactive map features), serve the files using a local web server.

Using Python 3:
```bash
python -m http.server 8000
```
Then navigate to [http://localhost:8000](http://localhost:8000) in your browser.

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss your ideas.

## License

This project is licensed under the MIT License. For more details, please see the [LICENSE](LICENSE) file.

## Acknowledgements

- [ArcGIS JavaScript API](https://developers.arcgis.com/javascript/)
- [Font Awesome](https://fontawesome.com/) for iconography
- The open-source community for inspiration and support
```

After creating and saving this file as `README.md` in your project folder, remember to add, commit, and push it to your GitHub repository:

```bash
git add README.md
git commit -m "Add README.md file for Natural Resources of Egypt project with ArcGIS integration"
git push origin master
```

*Note: Replace `master` with `main` if your default branch is named `main`.*
