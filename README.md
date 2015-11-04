## Web Performance Optimization portfolio project
####Super complex! instructions to run the application
- Download zip file or clone in desktop
- Then open index.html in a web browser


####Part 1: Optimize the PageSpeed Insights score for file index.html

Optimizations:
- a) Added media print to print.css file
- b) added async to analytics.js file
- c) Updating images: created a thumbnail for pizzeria.jpg, update img src url for pizzeria.jpg, reduced img profile picture
- d) Moved google fonts to the top of the head node
- e) inlined javascript google font
- f) inlined relevant style.css
- g) left style.css file untouched, but added media=handset for the smaller portrait @media style


####Part 2: Optimized Frames per Second in pizza.html file

####To optimize views/pizza.html, modify views/js/main.js until  frames per second rate is 60 fps or higher. See comments in main.js.

- a) Changed paint pizzas from 200 to 35 (4 rows of 8 cols)
- b) moved the dx function call outside of the for loop. It needs to be run only once; the value only changed when the slider is moved.
- c) added meta content to pizza.html file
- d) compressed pizza.jpg image
- e) set document.queryselectorAll to 100
- f) resized pizzaria.jpg pic
- g) Inlined minified style.css into pizza.html file
