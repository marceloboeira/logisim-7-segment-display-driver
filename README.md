# 7 Segment Display Driver
> TTL-7447-like implementation for logisim

The 7-segment display driver is an implementation of or BCD (Binary Coded Decimal) to 7-segment display decoder and driver.

It allows you to send binary numbers to a 7 segment display rather than implementing every character yourself.

## What is Logisim ?

Logisim is a circuit simulator. More info: http://www.cburch.com/logisim/

## How to use ?

### Step 1

First of all you will need to download the this project (link),  or clone.

Then create a new circuit pressing "CTRL + N".

See:

![1](https://github.com/marceloboeira/logisim-7-segment-display-driver/raw/master/_res/how-to-1.png)


### Step 2

Right click at your circuit folder, go to "Load Library" > "Logisim Library" then find the "7-segment-display-drive.circ" file

![2](https://github.com/marceloboeira/logisim-7-segment-display-driver/raw/master/_res/how-to-2.png)


### Step 3

After loading the library, you need to add the component to your circuit.

It's easy to see down in the list, the component:

![3](https://github.com/marceloboeira/logisim-7-segment-display-driver/raw/master/_res/how-to-3.png)

### Step 4

Make your circuit, and remember the display pins are:

![Display](https://github.com/marceloboeira/logisim-7-segment-display-driver/raw/master/_res/display.png)

So, after connecting the Driver to the display, your circuit should look like this:

![4](https://github.com/marceloboeira/logisim-7-segment-display-driver/raw/master/_res/how-to-4.png)


## Examples

Inside the examples folder, you can see some circuits:

### Example 1 - Switch

![Example 1](https://github.com/marceloboeira/logisim-7-segment-display-driver/raw/master/_res/example-1.gif)

### Example 2 - Flip Flop JK (Async)

![Example 2](https://github.com/marceloboeira/logisim-7-segment-display-driver/raw/master/_res/example-2.gif)

## Docs

Here you can see the Truth table, that I used to make the circuit:

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
