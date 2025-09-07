# Nixie Tube Stats Display

![Nixie Tube Stats Display](https://via.placeholder.com/800x400?text=Nixie+Tube+Stats+Preview)

A stunning, interactive web component that displays statistics using realistic Nixie tube-style bulbs with authentic animations and glow effects.

## Features

- 🎛️ **Realistic Nixie Tube Design**: Each statistic is displayed in a beautifully rendered glass bulb with authentic curvature and materials
- 🔢 **Multi-digit Support**: Numbers like "130" are displayed across multiple individual tubes (1, 3, 0)
- 💡 **Authentic Glow Effects**: Warm orange glow with realistic flickering and pulsing animations
- 🌀 **Realistic Digit Changes**: Numbers change with authentic Nixie tube behavior - digits fade out before the next one appears
- 🌊 **Glass Refraction Effects**: Curved glass appearance with light refraction and reflections
- 🕹️ **Interactive Elements**: Subtle parallax effects when hovering over tubes
- 📊 **Responsive Design**: Works on various screen sizes
- 🎚️ **Smooth Animations**: Numbers count up with randomized flickering for an authentic warm-up effect

## Installation

Simply download or clone this repository, then open `index.html` in any modern web browser.

No build tools or dependencies required!

## Usage

1. Open the `index.html` file in your web browser
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