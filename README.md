# Projects for Beginner Coders

This is a list of projects that beginners might enjoy to make. See `about.md`
for more information. These projects should be “easy” in the sense that they
don’t contain that many parts that need to work together.

They are organized by “type” — not by what area of computing they touch upon
(filesystems, networking, graphics) — but by what type of person they might
appeal to.

## General tips

Python is a great language for beginners. If you want to make graphics,
[turtle] is a great library that comes with Python!

## Words and literature

* Check for palindromes
* Combine letters in normal ways to generate pronounceable but fake words
  * Challenge: implement some of the real [English syllable structure rules][syl]
* Using [a list of Greek and Latin root words][roots], combine them randomly to
  make real-sounding but fake words
* Fill out “mad libs”-type “build your own story” paragraphs
* Generate sentences
* Make a [Ceasar cipher][ceasar]
  * Bonus: have a friend make one as well; exchange encoded texts and see if you
    can decode theirs
* Generate descriptions for your favorite type of scene; an example description
  for a garden might read: `The garden has flowers and corn. The flowers are
  visited by bees. The sky above is blue.`
* Create a “text speak” converter by stripping words of vowels

## Visual art and pictures

* A [spirograph]
* A utility for resizing images. For Python, use [Pillow] to load images
  * Challenge: let the user choose between several modes of resizing; average
    areas in the source image to create smoother pictures
* Generate random gradients. Can you figure out rules to make them as pretty as
  possible?
* Simulate [Conway’s Game of Life][conway], starting with noise (i.e.
  randomly-generated cells)
* Fill a space with circles that touch at the edges
  * Doing this while minimizing empty space is called “[circle packing][circlepacking]”
    and is the subject of continued research

## Games

* Tic-tac-toe
* Rock paper scissors
* Dice; ask the user for a die number (d6, d10, d20, etc.) and generate a random
  number
  * Bonus: ask for their [DnD] stats and compute a corrected score; print
    “Natural 20” for a 20 and “critical miss” for a 0
* Hangman
  * Bonus: have the *user* enter a word and the computer guess. What happens
    when the user lies?
* Chess move validator; assume there are no pieces blocking a potential move but
  use each piece’s rule-set to determine where *might* be a valid move
* Battleship

## Math

### Fractal

Fractals are shapes which repeat themselves, such as the [Sierpinski
triangle][sierpinski]

* Draw [the Mandelbrot set][mandelbrot]; print it to the console, using `#` to
  indicate a point that is in the Mandelbrot set and empty space to indicate a
  point that is not.
  * You’ll need to perform arithmetic on complex numbers
  * Challenge: create a window and display it on the screen

### Geometry

* Ask the user for a side-length and an angle of a right triangle and use
  trigonometry to figure out the rest of the angles and side-lengths.
* Ask the user for two points on a line and print out its intersection with the
  x and y-axis as well as its slope.
* Ask the user for a circle’s radius, diameter, circumference, or area and tell
  them the rest of the information about the circle

### Calculus

* Ask the user for polynomial coefficients and calculate the derivative (and/or
  integral)
* Display the slope-field of a differential equation
  * Taking user input is much harder than it sounds — just code the formula into
    your program
* Use a rectangular or trapezoidal approximation to calculate a definite integral

### Algebra

* Make a program for solving the quadratic equation (ask the user for the value
  of *a*, *b*, and *c*)
  * Challenge: gracefully handle imaginary roots
  * Challenge: accept binomial pairs as input (e.g. `(x + 2)(x - 3)`)

### Arithmetic

* Convert decimal numbers to fractions
  * Warning: surprisingly difficult

### Statistics

* Given a set of points, perform a [linear fit][linearfit]
  * Challenge: tell the user how accurate the fit is
  * Challenge: Add other types of fits: quadratic, sinusoidal, etc.

## Finance

* Tally monthly expenses and determine how much you’ll spend on them in a year,
  5 years, and 10 years.
  * Warning: potentially depressing.
* Ask for monthly deposits (and other info) and determine the savings upon
  retirement
  * Challenge: determine, given a certain monthly spending rate, how long the
    savings will last

[karan]: https://github.com/karan/Projects
[turtle]: https://docs.python.org/3/library/turtle.html
[mandelbrot]: https://en.wikipedia.org/wiki/Mandelbrot_set
[spirograph]: https://en.wikipedia.org/wiki/Spirograph
[syl]: http://clas.mq.edu.au/speech/phonetics/phonology/syllable/syll_structure.html
[roots]: https://en.wikipedia.org/wiki/List_of_Greek_and_Latin_roots_in_English
[ceasar]: https://en.wikipedia.org/wiki/Caesar_cipher
[DnD]: https://en.wikipedia.org/wiki/Dungeons_%26_Dragons
[sierpinski]: https://en.wikipedia.org/wiki/Sierpinski_triangle
[Pillow]: https://pillow.readthedocs.io/en/latest/
[linearfit]: https://en.wikipedia.org/wiki/Linear_regression
[conway]: https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life
[circlepacking]: https://en.wikipedia.org/wiki/Circle_packing
