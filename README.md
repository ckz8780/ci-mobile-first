# Welcome! 

This is a quick demonstration of the principles of mobile first design. Try resizing your browser. Below 992px width, left and right margins are removed and columns become full width. Otherwise there is a 10px margin on all sides and the columns take up 30% of the screen each, providing a horizontal layout for larger screens.

This project has been lightly extended to:

- Add a header to the page
- Add a border radius of 5px to the columns
- Change the background color of the columns
- Display the columns as inline-block for screens above 992px, which allows us to...
- Center the set of 3 columns on larger screens, rather than using float: left

Take a look at the CSS and compare it to the [desktop-first repo](https://github.com/ckz8780/ci-desktop-first). Notice the use of the `min-width` media query in this repo vs the `max-width` query in the other.

The index is at https://ckz8780.github.io/ci-mobile-first/index.html