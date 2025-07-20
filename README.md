# SVG SCADA Tools

This project provides tools for visualizing, animating, and identifying elements in SVG diagrams, specifically for SCADA (Supervisory Control and Data Acquisition) and water tank systems.

## Files

- **airgerak.html**
  - Animates the water level in `tangki.svg` and provides a toggle to show/hide live annotation overlays for all SVG elements with `id` or `data-cell-id` attributes.

- **identify_svg_ids.html**
  - Loads `tangki.svg` and lists all `id` and `data-cell-id` attributes in a readable format.
  - Visually annotates each SVG element with a label and a line pointing to the top-right corner of its bounding box.

- **tangki.svg**
  - The main SVG file representing the water tank. Elements in this SVG can be animated and annotated by the HTML tools above.

## Usage

1. Place your SVG file (e.g., `tangki.svg`) in the same directory as the HTML files.
2. Open `airgerak.html` in your browser to see the animated tank and toggleable annotation overlays.
3. Open `identify_svg_ids.html` to see a list and visual annotation of all `id` and `data-cell-id` attributes in your SVG.

## Features

- **Live Animation:** Water level in the tank animates up and down.
- **Annotation Toggle:** Show/hide overlays and lines for all SVG elements with `id` or `data-cell-id`.
- **ID/Data-Cell-ID Listing:** Quickly identify all key SVG elements for scripting or integration.

## Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari)
- No server required; works with local files (may need to use a local server for SVG fetch in some browsers)

## License

MIT License
