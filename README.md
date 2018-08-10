# Projects for Beginner Coders

This is a list of projects that beginners might enjoy to make. See the
“rationale” section at the bottom for details. These projects should be “easy”
in the sense that they don’t contain that many parts that need to work together.

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
triangle][sierpenski]

* Draw [the Mandelbrot set][mandelbrot]; print it to the console, using `#` to
  indicate a point that is in the Mandelbrot set and empty space to indicate a
  point that is not.
  * You’ll need to perform arithmetic on complex numbers
  * Challenge: create a window and display it on the screen

### Geometry

* Ask the user for a side-length and an angle of a right triangle and use
  trigonometry to figure out the rest of the angles and side-lengths.

### Arithmetic

* Convert decimal numbers to fractions
  * Warning: surprisingly difficult

## Finance

* Tally monthly expenses and determine how much you’ll spend on them in a year,
  5 years, and 10 years.
  * Warning: potentially depressing.
* Ask for monthly deposits (and other info) and determine the savings upon
  retirement
  * Challenge: determine, given a certain monthly spending rate, how long the
    savings will last

# Rationale

Many of the lists of projects for beginners out there are Bad. The projects
usually fall into one or both of two categories:

1. **Extremely uncompelling** — these projects are not *interesting*; they don’t
   solve a problem. I had the most fun as a kid when I was making things to “do
   something cool” for me, whether it was generating fake practice charts for
   band class, making a program to solve my math homework problems, or making
   programs to draw cool pictures on my TI-83.

   Examples: Generate a bunch of prime numbers, make an alarm clock, make a
   checkbook, implement Dijkstra’s algorithm.

2. **Extremely difficult** — I’ve seen lists of [“projects anyone can do”][karan]
   filled with projects that would stump me today.

   Examples: Make an FTP server, make a syntax highlighter, make a regex parser.
   Many of these are *also* very uncompelling for people who don’t already code!

# To-Do

* Add a glossary and key words (like “string concatenation” or “permutation”) to
  ideas

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
