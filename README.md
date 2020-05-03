# Chess-EPDs
# Various EPD test suites, Public Domain, no Copyright should apply.
# Where known, EPD original source credited.
# Collected up from various Internet sources.

# This batch all have bm = 'BestMove' indicated.
# ===========================================
# 900 plus random positions
  benchmark.epd	
# famous test from 1980's
  bratko-kopec.epd
# designed to break EPD handlers, some are valid chess positions, some not
  destruction-test.epd
# fortress positions
  fortresses.epd
# anything that caused issues at one time or another
  grief-causers.epd
# positions credited to Larry Kaufman
  kaufman.epd
# LC2 test positions
  lct2.epd
# various test positions, some duplicates
  mixed.epd
# nolot test positions
  nolot.epd
# from Rybka forum
  rybka-forum.epd
# Dann Corbitt quiet positions
  silent-but-deadly.epd

# PERFT tests, with nodecount at various minimax search depths.
# =============================================================
# Side to move is in double check (thanks to Ferninand Mosca)
  perft-ferdy-double-checks.epd	
# 6000 plus positions (thanks to Marcel van Kervinck for placing in PD)
  perft-marcel.epd
# Perft stress testers, designed to catch special moves (en passent, castles, promotions, in check and so on)
  perft.epd
