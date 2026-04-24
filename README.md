# 3D Home Colour Visualizer (2/56B) 🎨🏡

A completely client-side, interactive 3D room and exterior paint visualizer built for seamless color selection and planning. Designed specifically to streamline communication with professional painters.

## Features ✨

* **Interactive 3D Interior:** Visualize paint colors on different walls with real-time SVG rendering. Includes options to pair opposite walls.
* **Exterior Elevation Builder:** Test 30/70 split dado styles, border lines, and colors on the home's exterior elevation.
* **Lighting Modes:** See how exterior colors react to Day, Dusk, and Night lighting conditions.
* **Categorized Paint Library:** Features 40+ trending colors from **Asian Paints (Apcolite Premium)**, carefully categorized into Whites, Neutrals, Blues, Greens, Earth, Yellows, and Greys.
* **PDF Summary Generator:** One-click generation of a detailed PDF containing room-by-room 3D snapshots, exact color codes, and specific paint finishes (Matte vs. Silk/Washable) to hand over directly to the painter.

## How to Use 🚀

This is a zero-dependency front-end application.
1. Download or clone the repository.
2. Open `index.html` in any modern web browser (Chrome, Edge, Safari, Firefox).
3. No backend server or installation required.

## Tech Stack 🛠️

* HTML5, CSS3 (Native, no frameworks)
* Vanilla JavaScript (ES6+)
* [jsPDF](https://github.com/parallax/jsPDF) (Client-side PDF generation)

## Professional Paint Guidelines 🖌️

The application automatically recommends finishes based on color depth and room utility:
* **Dark Accent Walls (e.g., Deep Teal, Deep Navy):** Use **Matte finish** to avoid glare, enhance color richness, and hide plaster imperfections.
* **Light Base Walls (e.g., Pristine, Warm Sand):** Use **Silk / Washable finish** for stain resistance and easy maintenance.
* **Kitchen:** High-washable emulsion for oil and stain resistance.
* **Exterior:** * Upper Wall (70%): Apex Ultima (Dust/Rain Proof)
  * Base Dado (30%): Apex Advanced (Tougher protection against ground soil)
  * Wood/Metal: Premium Gloss or Matte Enamel
