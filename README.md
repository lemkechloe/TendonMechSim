# TendonMechSim

An educational web simulation modeling Achilles tendon regeneration and mechanical loading over a 28-day timeline, developed for BME 5313 Cellular Mechanobiology.

## Overview

TendonMechSim is a client-side web application designed to demonstrate the effects of mechanical tension on tendon extracellular matrix remodeling following surgical repair.

The application includes three primary modules:
1. **Academic Dashboard**: 2D tendon cross-section visualization with toggleable heatmaps (strain, collagen content, fibril orientation), clinical preset scenarios, and dynamic stiffness curves.
2. **Interactive Sandbox**: Real-time interactive model with live metrics (strain, load, day counter) and post-simulation performance review.
3. **Rehab Clinic Challenge**: A step-by-step 4-week protocol wizard where users prescribe weekly loads to optimize tendon recovery across different tissue profiles.

## Running the Simulation

No build steps or server setup are required:
- Simply open `index.html` in any modern web browser.
- Alternatively, enable **GitHub Pages** under repository settings (`main` branch / root) to host the project online.

## Project Structure

- `index.html` - Single-page web application using Tailwind CSS and Chart.js.
- `README.md` - Project documentation.
- `.gitignore` - Standard Git ignore rules.

## Author & Course

- **Author**: Chloe Lemke (chloe.lemke@gmail.com)
- **Course**: BME 5313 Cellular Mechanobiology
- **Scientific Reference**: Computational tendon remodeling model based on Notermans et al. (2021).
