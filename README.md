# Laundry Service - CSS Hero Section Assignment

## Project Overview
This project is a web application frontend for a laundry service. It was designed to fulfill specific layout constraints, focusing on traditional CSS positioning techniques and responsive viewport units to create a seamless, single-screen user experience.

## Key Objectives & Requirements Met
* *Navbar Construction (Without Flexbox):* The navigation bar was built strictly using display: inline-block and float properties (logo floated left, username floated right, links centered) to demonstrate mastery of traditional layout methods before adopting Flexbox.
* *Viewport Fit (No Scrolling):* The webpage is designed to fit exactly on one screen. The body element uses height: 100vh, width: 100vw, and overflow: hidden. The viewport height is strictly divided between the Navbar (12vh) and the Hero Section (88vh).
* *Hero Layout:* Created a split-screen hero section using inline-block elements (left-div and right-div). Vertical centering was achieved using the ::before pseudo-element trick combined with vertical-align: middle.
* *Responsive Typography:* Utilized viewport width (vw) units for heading and paragraph text to maintain design proportions across different screen sizes.

## Tech Stack
* *HTML5:* Page structure.
* *CSS3:* Custom styling, layout without Flexbox, Viewport units (vh, vw).

## How to Run
1. Extract the project files to a local directory.
2. Open the index.html file in any modern web browser (Google Chrome, Firefox, Safari, Edge).
3. No local server or external dependencies are required.

## File Structure
* index.html - Contains the complete HTML structure .
* style.css - contataing the style applied on HTML.