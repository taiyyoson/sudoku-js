# Sudoku Game

## Purpose

My girlfriend has recently gotten REALLY into the NYTimes mini-games, but doesn't have a subscription. She feels content about all the daily games, with the EXCEPTION of sudoku. She gets sad when she can only play it once per day, so I thought what better than to make my own? It's not too difficult to make, and it's good practice to teach myself a little more JavaScript. So, that's what I did

## Implementation

I have a basic trio of files: `sudoku.css`, `sudoku.html`, and `sudoku.js`. 

I link the files together in the .html using `<link></link` and `<src></src>`. CSS is for styling, HTML is for the frame, and JS is for the coding. It's ideal because there's a lot I can do with js.

## Game
<img width="1430" alt="Screenshot 2024-03-14 at 11 43 18 PM" src="https://github.com/taiyyoson/sudoku-js/assets/123409233/b58686e6-bf20-4ba6-9c9d-284f2491cac7">
**Version 1.0**


## Edit Notes

I have a couple notes that I will be implementing in the future

`.css`: 
 - fancier UI
 - Customize title, background
 - different font options?
 - title 
 - timer
 - when finish inputting all of one number, digit key turns darker grey
 - when error increments, keep input, but highlight number in red

`.js`:
 - add keyboard EventListener
 	- includes arrow keys to navigate puzzle
 - different difficulties
 	- this includes randomizing numbers of puzzle to solve (this may be hardest part of v2 implementation)
 - auto-solve buttom
 	- learn and utilize backtracking algorithm; [Link here:](https://en.wikipedia.org/wiki/Sudoku_solving_algorithms)
 - auto-checking feature INSTEAD of auto errors
