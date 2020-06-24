# Chess-EPDs
------------
Various EPD test suites, Public Domain, no Copyright should apply.
Where known, EPD original source credited.
Collected up from various Internet sources.

# Added Odds-suites in three directories
1. Normal opening type positions
2. Random opening type positions
3. Master lists for nite-odds for gauntlet testing. These are the nites-odds suites that testers should use in order
to remain consisent with each other.

There are suites for knight-odds, bishop-odds, rook-odds, queen-odds, pawn-f2-odds and a few others.
Probably the knight odds are the most useful.
The Normal opening types suites contain mostly chess-normal positions and are the better ones to use for testing purposes.

At time of writing, testes are seemingly showing that Stockfish 11 (latest version) is able to give knight odds
against Grandmaster strength chess engines from several years ago and achieve a 50-50 result.

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

3000 plus positions with en passant check involved (thanks to Ferninand Mosca)
ferdy_perft_enpassant_1.epd

180 positions with double check involved (thanks to Ferninand Mosca)
ferdy_perft_double_checks.epd



  

  
