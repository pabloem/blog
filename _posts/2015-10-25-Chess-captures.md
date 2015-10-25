---
layout: post
title: The Chess Battlefield
tags:
  - chess
  - data analysis
  - millionbase
---

I recently analyzed [the millionbase](http://www.top-5000.nl/pgn.htm). A large dataset of aproximately 2.2 million chess games. There have been several examples of analyses of the millionbase, such as the [Chess Piece Journeys](https://www.reddit.com/r/dataisbeautiful/comments/37yg35/chess_piece_journeys_album_oc/), and [Survival of Pieces in Chess](https://www.reddit.com/r/dataisbeautiful/comments/2jrwgw/survival_of_pieces_in_chess/) that was first posted in Quora. 

Inspired by these, I decided to analyze how pieces are captured on the Chess Board. The result is the following visualization:

## Where piece captures occur
<iframe src="http://pabloem.github.io/chess/full_captures.html" width="750" height="550" frameborder="0" scrolling="no"></iframe>

The results were quite interesting. For instance, how the center of the board is where most piece captures occur. Observe, though, that the distribution becomes much less concentrated around D4 and E5 for pieces that are not pawns. Queens, bishops, and knights are often captured in the middle of the board, but their distributions have a much higher variance; and rooks are most often captured on the edges of the board.

The data, as well as the code for the analysis and visualization are available on my Git repository. Feel free to ask any questions, or use the code as you see fit. Please give attribution to me when you use the visualizations.
