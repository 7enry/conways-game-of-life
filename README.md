# conways-game-of-life
This project implements Conway’s Game of Life in Python, with animation, pattern parsing, and Turing machine simulation.

Setup instructions:
1. download and unzip file
2. run virtual environment (optional)
3. install required dependencies (pip install numpy scipy matplotlib)

Supported Pattern Formats:
Plaintext (.cells)
RLE (.rle)

.
├── conway.py                     # Main GameOfLife class
├── rle.py                        # RLE pattern parser
├── test_gameoflife_glider.py     # Animated glider demo and runs Plaintext patterns
├── test_gameoflife_glider_simple.py  # Static test with blinker
├── test_gameoflife_turing.py     # Loads and runs Turing machine pattern or other RLE patterns
├── *.rle                         # Sample RLE files
├── *.cells                       # Sample CELL files
└── README.md
