# Q1-Project
Q1 project, Boggle

The night before these projects were due I committed, pushed, and deployed an MVP of this product. It can be found in the root of https://github.com/danaholivetree/q1proj and at http://dan-boggle.surge.sh/

This version here incorporates some features and functionality that I was not able to have ready in time for presentations last week.

In this game:

Users can click and drag to draw words from adjacent letters. Letters highlight as you add them to the word, and you can't re-add a letter you've already highlighted. Alternately, you can type words to enter them, but I haven't yet gotten the grid to respond if you choose letters out of sequence. Both methods of submitting words will go through three levels of validation-- one to make sure the word meets the minimum length requirement, one to make sure the letters typed are all at least on the grid, and one through a dictionary API to make sure the word is 'real'.

This game also allows you to choose your grid size, minimum score-able word length, and starting timer. It will keep track of your successful words in a list, and tally up their point values. At the end of the time limit, the timer stops and a message informs you of your total score. You then have the option to reset the board and play again.

I'll be continuing to work on this game. My goal is to first be able to add adjacent-letter validation to the keypress input. I'd also like to replace the current dictionary API with the Merriam-webster API for dictionary validation. that requires parsing XML, which i didn't get a chance to figure out how to do during the scope of this project.
