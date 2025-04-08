<h1>Product Filter Mini Project</h1>

Overview

This project is a Product Filter application built using HTML, CSS, and jQuery. It allows users to filter a list of products by categories like Shoes, Sandals, and Heels. The filtering is done dynamically, and the page is responsive to ensure a seamless user experience across different devices.

Features

Category Filter: Filter products by categories such as Shoes, Sandals, and Heels.

Responsive Design: The layout adapts to different screen sizes (desktop, tablet, and mobile).

Fade-in and Fade-out Animations: Smooth animations are used when switching between product categories.

Interactive Buttons: Buttons change the active state when clicked, highlighting the selected category.

Technologies Used
HTML5: Markup for structuring the page.

CSS3: Styling and layout for a clean and responsive design.

jQuery: Used to handle the filtering functionality and smooth animations.

Responsive Design: The project adapts to various screen sizes (mobile-first approach).

Live URL
View Demo (You can insert a link to your hosted demo here)

How It Works
1. Page Load
When the page loads, all the product images are displayed. The Show All button is selected by default, showing all products.

2. Filtering Products
The user can click on one of the category buttons (Shoes, Sandals, or Heels) to filter products based on their selection. The categories are displayed in a grid, and only the items corresponding to the selected category will be visible.

3. Animations
The product images fade in and fade out smoothly when switching between different categories.

Project Structure
/product-filter-mini-project
|-- index.html       # Main HTML file
|-- /images          # Folder containing product images
|-- /css             # Folder containing styles (styles are inline in this project)
|-- README.md        # Project documentation (this file)
File Description
index.html
This file contains the markup for the application, including:

The main title and description.

Category buttons for filtering.

A grid layout for displaying product images.

The jQuery script to enable filtering functionality and animations.

CSS Styling
The styles are embedded within the HTML file, ensuring a simple design that is mobile-responsive. Media queries ensure that the layout adjusts based on the screen size.

JavaScript (jQuery)
The jQuery script provides the filtering functionality:

When a category button is clicked, it hides all products, then shows the products belonging to the selected category.

The active button state is updated dynamically to provide visual feedback on the selected filter.

Responsive Design
Desktop: The page shows products in multiple columns.

Tablet: The layout switches to two columns.

Mobile: The layout adjusts to a single column for easy viewing.

Media Queries
For screens with a width of 768px or less, the layout changes to display 2 columns.

For screens with a width of 480px or less, the layout switches to a single column to optimize for smaller devices.
