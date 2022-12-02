# [Arduino] Character Editor for TM1637 Display Library

### [https://icetinturkey.github.io/Custom-Character-for-TM1637.h](https://icetinturkey.github.io/Custom-Character-for-TM1637.h)
#
### How to add new character;
##### 1) Install Grove 4-Digit Display Library.
![Image](https://lh3.googleusercontent.com/drive-viewer/AFDK6gNLk00Faluyg2zrX2H5Q5nZhB10nfOB0sDBJbJTYz6538h8ZYRYlxghFGDIA5NLPBWu0QDardU6KT9wnH7ZEb1Gwhbc=w1504-h607)
##### 2) [`Go character editor`](https://icetinturkey.github.io/Custom-Character-for-TM1637.h) and click 'Create New Character'
##### 3) Select option 16 in the panel on the right.
##### 4) Draw the character you want by clicking on the sectors and click 'Save'.
##### 5) Download the new library file by pressing the 'Export File' button.
##### 6) Replace C:\Users\{Username}\Documents\Arduino\libraries\Grove_4-Digit_Display\TM1637.cpp with the file you just downloaded.
#
### How to use my new character (In the example above: 16)
##### Firstly we must import libraries: `#include "TM1637.h"` and `TM1637 tm1637(CLK_PIN,DIO_PIN);`
##### Usage: `tm1637.display({digit number},{character id});`
##### Example: `tm1637.display(0,16);`
