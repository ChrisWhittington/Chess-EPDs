# Chess-EPDs
------------
Various EPD test suites, Public Domain, no Copyright should apply.
Where known, EPD original source credited.
Collected up from various Internet sources.

This batch all have bm = 'BestMove' indicated.
----------------------------------------------
900 plus random positions
benchmark.epd	
  
famous test from 1980's
bratko-kopec.epd
  
designed to break EPD handlers, some are valid chess positions, some not
destruction-test.epd
  
fortress positions
fortresses.epd
  
anything that caused issues at one time or another
grief-causers.epd
  
famous test positions credited to Larry Kaufman
kaufman.epd
  
famous LC2 test positions
lct2.epd
  
various test positions, some duplicates
mixed.epd
  
famous nolot test positions
nolot.epd
  
from Rybka forum
rybka-forum.epd
  
famous Dann Corbitt quiet positions
silent-but-deadly.epd
  
PERFT tests, with nodecount at various minimax search depths.
-------------------------------------------------------------
Format is: FEN D5 nodecount, where D=depth and nodecount=number of minimax nodes at depth D
Most (if not all) have been tested against several engines, each time with same nodecount result,
so they should be reliable enough. 

Perft stress testers, designed to catch special moves (en passent, castles, promotions, in check and so on)
perft.epd

Side to move is in double check (thanks to Ferninand Mosca)
perft-ferdy-double-checks.epd	
  
6000 plus positions (thanks to Marcel van Kervinck for placing in PD)
perft-marcel.epd

these last two have not been give a final checkover, but passed two engines worth of testing so far
---------------------------------------------------------------------------------------------------
5000 plus positions each with check involved (thanks to Ferninand Mosca)
ferdy_perft_single_check_1.epd to ferdy_perft_single_check_19.epd

3000 plus positions with en passent check involved (thanks to Ferninand Mosca)
ferdy_perft_enpassent_1.epd



  

  
