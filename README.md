# CLIMETA Website

## Overview
This project is an HTML-based online shop for eco-friendly products related to climate change awareness. It includes various products such as reusable bags, T-shirts with environmental messages, and books on climate change and sustainability.

## Files Included
- **index.html**: Main HTML file containing the structure of the online shop interface.
- **student1_style.css**: CSS file for styling the online shop interface.
- **shop_form.html**: This file is referenced for the checkout process (not provided in the code snippet).
- **Images**: Various image files (PNG, JPEG) used for product display.
- **README.md**: This file, providing an overview of the project.

## Features
1. **Navigation**: Navigation bar with links to Home, Shop (active page), User Profile, Feedback, and About Us.
2. **Product Showcase**: Divided into sections showcasing different categories of products (T-Shirts, Bags, Books).
3. **Product Details**: Each product includes an image, price, description, customization options (radio buttons), and a quantity input.
4. **Dynamic Filtering**: Dropdown menu allows users to filter products by category (All items, T-Shirts, Bags, Books).
5. **Shopping Cart**: Displays an order summary with added items, total price, and buttons to clear the cart or proceed to checkout.
6. **Interaction**: Add to Cart buttons for each product dynamically add items to the cart with quantity and customization details.
7. **Responsiveness**: Designed to be responsive with a viewport meta tag for different device sizes.

## Usage
- Open **index.html** in a web browser (preferably Chrome, Firefox, or Edge).
- Navigate through product categories using the dropdown menu.
- Customize and add products to the cart by adjusting quantity and selecting options.
- Review the order summary in the cart section.
- Click "Empty cart" to remove all items or "Checkout" to proceed to the checkout process (referenced file **shop_form.html**).

## Notes
- This project is a static HTML interface with embedded JavaScript for cart functionality.
- The checkout functionality (`checkout-button` event listener) currently opens a placeholder link (`shop_form.html`) and should be linked to a real checkout process in a live implementation.
# Payment Details Form

## Overview
This HTML file provides a form for users to enter payment details and complete a purchase in an online shop setting. It includes fields for payment information, billing address, contact details, and order summary.

## Files Included
- **payment_details.html**: Main HTML file containing the payment details form.
- **student1_style.css**: CSS file for styling the payment details form.
- **README.md**: This file, providing an overview of the project.

## Features
1. **Payment Information**: Fields for card number, cardholder name, expiry date, and CVV.
2. **Billing Address**: Form fields for address, city, state/county, postcode/zip code, and country selection.
3. **Contact Details**: Fields for first name, last name, phone number, and optional email address.
4. **Order Details**: Displays the total price of the order retrieved from localStorage.
5. **Form Submission**: JavaScript function `formsubmit()` triggers an alert and attempts to close the window upon form submission.
6. **Reset and Submit Buttons**: Buttons to reset the form or submit payment details.

## Usage
- Open **payment_details.html** in a web browser (Chrome, Firefox, Edge, etc.).
- Fill in all required fields marked with a red asterisk (*).
- Review and confirm payment details, then click "Pay Now" to complete the purchase.
- Use the "reset" button to clear all form fields if needed.

## Notes
- This form is designed for demonstration purposes and does not process actual payments.

# Splash Screen

## Overview
This HTML file implements a splash screen for an online shop. It displays a logo and a loading animation when the page loads, providing a visual indication to users that content is being loaded.

## Files Included
- **index.html**: Main HTML file containing the splash screen.
- **student1_style.css**: CSS file for styling the splash screen.
- **ourlogo.png**: Image file used for the logo.
- **loader2.gif**: Animated GIF used for the loading animation.
- **README.md**: This file, providing an overview of the project.

## Features
1. **Splash Screen**: Displays a logo (`ourlogo.png`) and a loading animation (`loader2.gif`) when the page is loaded.
2. **Automatic Hide**: JavaScript script hides the splash screen after 4 seconds (`setTimeout` function).
3. **Responsive Design**: Designed to be responsive with the viewport meta tag.

## Usage
- Open **index.html** in a web browser (Chrome, Firefox, Edge, etc.).
- Observe the splash screen with the logo and loading animation upon page load.
- After 4 seconds, the splash screen automatically hides to reveal the main content of the online shop.

## Notes
- This splash screen provides a visual cue to users while the main content of the online shop is loading.
- Adjust the duration (currently set to 4 seconds) in the JavaScript `setTimeout` function as needed.
# Events Page

This page showcases various events related to sustainable development goals and initiatives.

## Table of Contents
- [Introduction](#introduction)
- [Events](#events)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Events Page provides information about upcoming events related to sustainable development, focusing on topics such as science, technology, innovation, and climate action. Each event is detailed with its purpose, date, and key highlights.

## Events

### 1. 9th Multi-stakeholder Forum on Science, Technology and Innovation for the Sustainable Development Goals

![Event 1 Image](trees.jpg)

The ninth annual Multi-Stakeholder Forum on Science, Technology and Innovation for the Sustainable Development Goals (STI Forum) will be held from Thursday, 9 May, to Friday, 10 May 2024. The forum will focus on the role of science, technology, and innovation in achieving sustainable development.

### 2. 2024 ECOSOC Partnership Forum

![Event 2 Image](fall.jpg)

The 2024 Partnership Forum of the Economic and Social Council (ECOSOC) was held on 30 January 2024 at the United Nations Headquarters. The forum discussed partnerships and actions to advance the 2030 Agenda for Sustainable Development.

### 3. Global Expert Group Meeting in preparation of the SDG13 review at the HLPF 2024

![Event 3 Image](lake.jpg)

The Expert Group Meeting (EGM) focused on SDG 13 (Climate Action) and its alignment with other Sustainable Development Goals. It aimed to accelerate global actions and policy frameworks to combat climate change.

### 4. Expert Group Meeting on SDG2 and its interlinkages with other SDGs

![Event 4 Image](mountain.jpg)

This Expert Group Meeting (EGM) discussed SDG 2 (Zero Hunger) and its role in promoting sustainable agriculture and food security. It highlighted strategies and partnerships to achieve the SDGs.

## Usage

To view event details:
- Click on "Read More" button under each event to expand the description.
- Navigate through the events using the navigation links provided.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or new event information to add, feel free to fork this repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

