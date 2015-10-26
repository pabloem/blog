---
layout: post
title: The Chess Battlefield
tags:
  - chess
  - data analysis
  - millionbase

---

I recently analyzed [the millionbase](http://www.top-5000.nl/pgn.htm). A large dataset of aproximately 2.2 million chess games. There have been several examples of analyses of the millionbase, such as the [Chess Piece Journeys](https://www.reddit.com/r/dataisbeautiful/comments/37yg35/chess_piece_journeys_album_oc/), and [Survival of Pieces in Chess](https://www.reddit.com/r/dataisbeautiful/comments/2jrwgw/survival_of_pieces_in_chess/) that was first posted in Quora. 

Inspired by these, I decided to analyze how pieces are captured on the Chess Board. The result is the following interactive visualization:

<iframe src="http://pabloem.github.io/chess/full_captures.html" width="750" height="550" frameborder="0" scrolling="no"></iframe>

The results are interesting - although they might be expected for anyone who's played chess for long enough. The center of the board is where most piece captures occur. A lot of it is from captures of pawns, which are very heavily captured in rows 4 and 5. Observe that the distribution becomes much less concentrated for pieces that are not pawns. Queens, bishops, and knights are often captured in the middle of the board, but their distributions have a much higher variance. Rooks on the other hand are most often captured on the edges of the board.

It is interesting to observe the patterns that form for black and white pieces, and for different pieces. Go ahead and spend some time looking at it. :)

The data, as well as the code for the analysis and visualization are available on my [Git repository](http://github.com/pabloem/chess/). Feel free to ask any questions, or use the code as you see fit. Please give attribution when you use the visualizations.
