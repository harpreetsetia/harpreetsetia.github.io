## Website Performance Optimization portfolio project

* To get started, check out the repository and inspect the code.

### Getting started

#### Part 1: Optimized the PageSpeed Insights score for index.html

1. Checkout the page speed insights at [https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fharpreetsetia.github.io%2F&tab=mobile](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fharpreetsetia.github.io%2F&tab=mobile)
2. Verify the result

#### Part 2: Optimize Frames per Second in pizza.html

1. Download repo ZIP file from [https://github.com/harpreetsetia/harpreetsetia.github.io](https://github.com/harpreetsetia/harpreetsetia.github.io)
2. Open views/pizza.html and check the fps in dev tools.

#### Part 3: Changes made in index.html

1. Minified assets.

2. Applied core styles as inline.

3. Deferred css calls per Google PageSpeed suggestion.

4. Deferred js calls where appropriate.

5. Applied loading of WebFonts per Google PageSpeed suggestion

#### Part 4: Changes in views/pizza.html and views/js/main.js

1. Modified the code to calculate the number of pizzas needed to fill the webpage based on browser inner dimensions.

2. Cached the needed DOM elements so that the brower isn't querying the DOM every time the for loops are iterated in the updatePositions and changePizzaSizes funcitons.

3. Changed all instances of querySelector to the more efficient getElementById and getElementByClassName depending on whether a class or id is needed.

4. In the changePizzaSizes function I created an additional for loop for setting the element's width. This was done to group all of the DOM calls and the Rendering together in separate loops. This prevents the browser from having to render the page over and over in between setting the styles.

##### Last Changes:
1. Updated views/pizza.html with correctly compressed images.
2. Updated views/js/main.js with changes in changeSliderLabel function.
# harpreetsetia.github.io
