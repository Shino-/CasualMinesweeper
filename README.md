# Casual minesweeper

[Minesweeper](https://en.wikipedia.org/wiki/Minesweeper_%28video_game%29) "as it should be", and by that I mean what it would look and feel, was it designed today with web technologies and new savoir-faire in UX.

## Early versions

1. `minesweeper_dom.html` used to store data about the cells directly in the DOM.
2. `minesweeper_beforeData.html` is snapshot, before the [jQuery](jquery.com) update which made `.data()` available.

## Current state

Most of the magic happens in a big module in index.html. It is designed with speed in mind, so with minimal dom touches (and sprites).

If anyone has friendlier graphics than the ones I shamefully stole... just contribute! But you do the sprite

## Trivia

[Minesweeper is NP-complete!](http://web.mat.bham.ac.uk/R.W.Kaye/minesw/ordmsw.htm)