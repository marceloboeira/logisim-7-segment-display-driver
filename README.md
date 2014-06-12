Converts BCD to 7 Segments Display
=====================================

## What is Logisim ?

http://ozark.hendrix.edu/~burch/logisim/

## Docs

 Coming soon!

![Display](https://github.com/marceloboeira/logisim-7-segment-display-driver/raw/master/_res/display.png)

![Truth Table](https://github.com/marceloboeira/logisim-7-segment-display-driver/raw/master/_res/truth.png)


| Hex | D | C | B | A |   | a | b | c | d | e | f | g |
|:---:|:-:|:-:|:-:|:-:|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|  0  | 0 | 0 | 0 | 0 |   | 1 | 1 | 1 | 1 | 1 | 1 | 0 |
|  1  | 0 | 0 | 0 | 1 |   | 0 | 1 | 1 | 0 | 0 | 0 | 0 |
|  2  | 0 | 0 | 1 | 0 |   | 1 | 1 | 0 | 1 | 1 | 0 | 1 |
|  3  | 0 | 0 | 1 | 1 |   | 1 | 1 | 1 | 1 | 0 | 0 | 1 |
|  4  | 0 | 1 | 0 | 0 |   | 0 | 1 | 1 | 0 | 0 | 1 | 1 |
|  5  | 0 | 1 | 0 | 1 |   | 1 | 0 | 1 | 1 | 0 | 1 | 1 |
|  6  | 0 | 1 | 1 | 0 |   | 1 | 0 | 1 | 1 | 1 | 1 | 1 |
|  7  | 0 | 1 | 1 | 1 |   | 1 | 1 | 1 | 0 | 0 | 0 | 0 |
|  8  | 1 | 0 | 0 | 0 |   | 1 | 1 | 1 | 1 | 1 | 1 | 1 |
|  9  | 1 | 0 | 0 | 1 |   | 1 | 1 | 1 | 0 | 0 | 1 | 1 |
|  A  | 1 | 0 | 1 | 0 |   | 1 | 1 | 1 | 0 | 1 | 1 | 1 |
|  B  | 1 | 0 | 1 | 1 |   | 0 | 0 | 1 | 1 | 1 | 1 | 1 |
|  C  | 1 | 1 | 0 | 0 |   | 1 | 0 | 0 | 1 | 1 | 1 | 0 |
|  D  | 1 | 1 | 0 | 1 |   | 0 | 1 | 1 | 1 | 1 | 0 | 1 |
|  E  | 1 | 1 | 1 | 0 |   | 1 | 0 | 0 | 1 | 1 | 1 | 1 |
|  F  | 1 | 1 | 1 | 1 |   | 1 | 0 | 0 | 0 | 1 | 1 | 1 | 