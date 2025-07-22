```markdown
# Contiguity Map with Flags - Force-Directed Graph of Countries

This project visualizes the geographical contiguity of countries as a force-directed graph using D3.js. Each node represents a country with its flag, and links show shared borders. The interactive graph allows users to drag nodes to explore the network dynamically.

---

## Features

- **Visualize borders** between countries with connecting lines.
- **Display flags** on each country node for quick identification.
- **Interactive drag-and-drop** for exploring the network.
- Fully responsive layout that adapts to window size.

---

## Demo

Check out the live demo [here](#) *(replace with your project link)*.

---

## How It Works

1. Loads country data from [this dataset](https://raw.githubusercontent.com/DealPete/forceDirected/master/countries.json).
2. For each country, fetches a flag image based on its country code.
3. Uses D3.js to create a force simulation where nodes (countries) are connected by borders.
4. Implements drag behavior for user interaction.

---

## Setup & Usage

### Prerequisites

- A modern web browser.
- Internet connection (for loading external data and images).

### Run the Project

1. Save the HTML code into a file, e.g., `index.html`.
2. Open `index.html` in your web browser.
3. Interact with the graph by dragging nodes to explore the country borders.

---

## Customization

### Changing Flag Sources

- The current setup fetches flags from [flagcdn.com](https://flagcdn.com).
- To use a different source or sprite sheet, modify the `getFlagUrl()` function in the script section.

### Styling

- Adjust background color or node size by editing the CSS or SVG attributes.
- Add labels or tooltips for more information.

### Data Source

- To use custom data, replace the JSON URL in the script with your own dataset.

---

## Troubleshooting

- **Flags not loading?**  
  Ensure CORS policies allow fetching images from the CDN used.
- **Graph not displaying properly?**  
  Check the console for errors and verify the dataset URL.

---

## License

This project is open-source and free to modify. Feel free to adapt it for your own use!

---

## Acknowledgments

- Dataset from [DealPete's GitHub Repository](https://raw.githubusercontent.com/DealPete/forceDirected/master/countries.json).
- Flag images from [Flag CDN](https://flagcdn.com).

---

## Contact

For questions or feedback, please contact Jordan Leturgez at jordanleturgez@gmail.com.

---

*Enjoy exploring the world with this interactive continent map!*
``

---

