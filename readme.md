# Nixie Tube Stats Display

![Nixie Tube Stats Display](img/Nixie%20Tube%20Stats%20Preview.jpeg)

A stunning, interactive web component that displays statistics using realistic Nixie tube-style bulbs with authentic animations and glow effects.

## Live Demo

View the current implementation: [https://madusanka-max.github.io/Nixie-tube/](https://madusanka-max.github.io/Nixie-tube/)

## Current Display

The webpage currently displays four statistics in a Nixie tube aesthetic:

1. **Years of Innovation**: Shows "0" (target: 1)
2. **Student Associations**: Shows "0" (target: 7) 
3. **Innovative Projects Showcased**: Shows "0 0 0" across three separate tubes (target: 1 3 0)
4. **Govt. & Private Sector Participation**: Shows "0" (target: 6)

## Features (After Implementation)

- 🎛️ **Realistic Nixie Tube Design**: Each statistic is displayed in a beautifully rendered glass bulb with authentic curvature and materials
- 🔢 **Multi-digit Support**: Numbers like "130" are displayed across multiple individual tubes (1, 3, 0)
- 💡 **Authentic Glow Effects**: Warm orange glow with realistic flickering and pulsing animations
- 🌀 **Realistic Digit Changes**: Numbers change with authentic Nixie tube behavior - digits fade out before the next one appears
- 🌊 **Glass Refraction Effects**: Curved glass appearance with light refraction and reflections
- 🕹️ **Interactive Elements**: Subtle parallax effects when hovering over tubes
- 📊 **Animated Count-up**: Numbers animate from 0 to their target values with randomized flickering
- 📱 **Responsive Design**: Works on various screen sizes
- 🎚️ **Smooth Animations**: Numbers count up with randomized flickering for an authentic warm-up effect

## Installation

Simply download or clone this repository, then replace the contents of your `index.html` file with the enhanced code provided.

No build tools or dependencies required!

## Usage

1. Open the `index.html` file in your web browser (or deploy to your GitHub Pages)
2. As you scroll to each statistic, the Nixie tubes will "warm up" and display their numbers with realistic animations
3. Hover over any tube to see a subtle parallax effect

## Customization

To modify the statistics:

1. In the HTML, find the `.number` elements
2. Change the `data-target` attribute to your desired number
3. Update the corresponding `.label` text

Example:
```html
<div class="number" data-target="42">0</div>
<div class="label">Your Custom Statistic</div>