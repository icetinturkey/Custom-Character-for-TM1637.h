### [Arduino] Character Editor for TM1637 Display Library
### [https://icetinturkey.github.io/Custom-Character-for-TM1637.h](https://icetinturkey.github.io/Custom-Character-for-TM1637.h)
#
### How to add new character
Install Grove 4-Digit Display Library.

##### ![Image](https://lh3.googleusercontent.com/drive-viewer/AFDK6gNLk00Faluyg2zrX2H5Q5nZhB10nfOB0sDBJbJTYz6538h8ZYRYlxghFGDIA5NLPBWu0QDardU6KT9wnH7ZEb1Gwhbc=w1504-h607)

[`Go character editor`](https://icetinturkey.github.io/Custom-Character-for-TM1637.h) then click 'Create New Character'

Select option 16 in the panel on the right.

Draw the character you want by clicking on the sectors and click 'Save'.

Download the new library file by pressing the 'Export File' button.

Replace C:\Users\\{Username}\Documents\Arduino\libraries\Grove_4-Digit_Display\TM1637.cpp with the file you just downloaded.

#
### How to use my new character (In the example above: 16)

Firstly we must import libraries: `#include "TM1637.h"` and `TM1637 tm1637(CLK_PIN,DIO_PIN);`

Usage: `tm1637.display({digit number},{character id});`

Example: `tm1637.display(0,16);`

#
### Finale
##### ![Image](https://lh3.googleusercontent.com/drive-viewer/AFDK6gNyRG8QpQBc-7phLQ5KXAX8umxak1wxJ13chSrv0wUyu-fmXszn9CWwa3Fkiz3U68JOeJVmuLxB6XOO8lOuwdVMmb7jIw=w1504-h607)
