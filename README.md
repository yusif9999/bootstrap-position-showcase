# Bootstrap Position Showcase: Smart Home UI

## Overview
This project is a responsive, single-page Smart Home Assistant interface built specifically to master Bootstrap 5 positioning utilities. It demonstrates the seamless integration of all fundamental position properties (`relative`, `absolute`, `sticky`, and `fixed`) alongside modern grid layouts and responsive display classes without relying on custom CSS.

## Key Features & Positioning Logic
* **Sticky (`position-sticky`):** Implemented on the top navigation header (`<header>`) to maintain persistent access to the menu while scrolling.
* **Relative & Absolute (`position-relative`, `position-absolute`):** Combined in the hero section to precisely anchor a "Limited Stock" promotional badge to the top-right corner of the main content container.
* **Fixed (`position-fixed`):** Applied to a floating "Quick Support" chat button, keeping it permanently anchored to the bottom-right corner of the user's viewport.
* **Responsive Display Management:** Utilized `.d-none`, `.d-md-block`, and `.d-md-none` to conditionally render a detailed technical table for desktop users and a specific warning prompt for mobile users.
* **Grid & Flexbox:** Structured using Bootstrap's native `.row`, `.col-*`, and flex utilities (`d-flex`, `justify-content-end`, `align-items-center`) for perfect alignment across devices.

## Technologies Used
* HTML5 (Semantic Structure)
* Bootstrap 5.3.8 (Layout & Utilities)
* Bootstrap Icons 1.13.1 (Typography & Icons)

## Usage
1. Clone this repository to your local machine:
   `git clone https://github.com/yourusername/bootstrap-position-showcase.git`
2. Open the `index.html` file in any modern web browser (e.g., Google Chrome, Firefox).
3. No local server, custom CSS, or external JavaScript files are required. The layout is powered entirely by Bootstrap via CDN.

## Author
* **Yusif Gaziyev**
