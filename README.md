# FizzBuzzGrid

A friend of mine had shared a partial post about a modified FizzBuzz challenge.  The challenge required creation of a 13 by 13 grid of squares. Squares were logically numbered 1 through 13 across the first row, 14 through 26 across the second, row.  Etc.  The number associated with each square when applied to the FizzBuzz computation should yield a color for the square that obeys the following rules:

- Blue for Fizz (evenly divisible by 3)
- Yellow for Buzz (evenly divisible by 5)
- Green for Fizz and Buzz (evenly divisible by 3 and by 5)
- Descending shades of gray for all other squares

I took a stab at this using PHP to generate HTML output.  Each square is a DIV with the characters XX in Courier New type at a 48-pixel font.  I just needed each DIV to be somewhat square.  I set the foreground and background color to the same value so that you couldn't see the X's.  Then, I followed the rules above to color each square.

The rendered output of the PHP script looks like this :

<img src="https://github.com/jimlawless/fizzbuzzgrid/fbg_rendered.png">

You can see the live page at:

https://jimlawless.net/fbg.php
