# SEDS_Nebula_AdVITya_24
These code snippets demonstrate the use of JavaScript concepts for implementing various functionalities:

1. **Event Listening and DOM Manipulation**:
   - The first part of the code deals with a navigation menu. It selects the menu button and navigation elements using `querySelector`, and adds a click event listener to the menu button. When the button is clicked, it toggles the "active" class on both the menu button and navigation elements.

2. **Iterating Over Elements and Functionality Implementation**:
   - The second part handles a video slider navigation. It selects buttons, slides, and contents using `querySelectorAll`, then defines a function `sliderNav(manual)` to handle slider navigation. It iterates over buttons and adds click event listeners to each, calling `sliderNav` with the index of the clicked button.

3. **Carousel Implementation**:
   - The third part implements a carousel functionality. It selects DOM elements related to carousel navigation, such as next and previous buttons, carousel container, slider, and thumbnails. It defines a function `showSlider(type)` to move the slider either to the next or previous slide based on the `type` parameter. It uses `setTimeout` for automatic sliding after a certain time interval and `clearTimeout` to reset the automatic sliding when user interacts with the carousel manually.

These snippets effectively demonstrate event handling, DOM manipulation, iterating over elements, and implementing functionalities like toggling classes for navigation, slider navigation, and carousel functionality.
