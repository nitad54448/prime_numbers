# Prime Number Visualizer (Ulam Spiral)

## Description

This is an interactive web-based application that visualizes prime numbers using an Ulam Spiral. Numbers are arranged in a square spiral, and prime numbers are highlighted in yellow, often revealing interesting and not fully understood diagonal patterns.

The application is built with HTML, Tailwind CSS, and plain JavaScript, rendering the visualization on an HTML Canvas.

## Features

* Interactive Ulam Spiral: Visualizes numbers in a spiral, highlighting primes.

* Logarithmic Scale: The "Numbers to Check" slider uses a logarithmic scale to efficiently explore a vast range of numbers, from 10 up to 50,000.

* Adjustable Dot Size: Control the size of the dots (or numbers in tutorial mode) for better visibility.

* Mouse Wheel Zoom: Hover over the spiral and use your mouse wheel to intuitively adjust the dot size.

* Tutorial Mode: For 100 numbers or fewer, the application displays the numbers themselves and draws connecting lines to clearly show how the spiral is constructed.

* Responsive Layout: The interface is designed with a resizable panel to adjust the view.

## How to Use

1. Open `index.html` in a modern web browser.

2. Numbers to Check: Use the top slider to select how many numbers you want to plot on the spiral. The display will update automatically. The app starts by showing the first 100 numbers.

3. Dot Size / Zoom:

   * Use the "Dot Size" slider to change the size of the elements.

   * Alternatively, hover your mouse over the canvas and use the mouse wheel to zoom in and out.

4. Resize Panel: Drag the vertical bar between the left control panel and the right canvas to resize the viewing area.

