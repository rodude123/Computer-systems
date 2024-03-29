# Logic gates

* Building blocks of how computers work

## Not Gate

|![NOT gate](https://www.computerscience.gcse.guru/wp-content/uploads/2016/11/NOT-1-255x127.png)|
|:---------------------------------------------------------------------------------------------:|
|                                      *Example of a NOT gate*                                  |

```Z = NOT A```

|A|B|
|:-:|:-:|
|0|1|
|1|0|

## And Gate

|![AND gate](https://www.computerscience.gcse.guru/wp-content/uploads/2016/11/AND-255x127.png)|
|:-------------------------------------------------------------------------------------------:|
|                                      *Example of an AND gate*                               |

```Z = A AND B```

|A|B|Z|
|:-:|:-:|:-:|
|0|0|0|
|0|1|0|
|1|0|0|
|1|1|1|

## Or Gate

|![OR gate](https://www.computerscience.gcse.guru/wp-content/uploads/2016/11/OR-255x127.png)|
|:-----------------------------------------------------------------------------------------:|
|                                      *Example of and OR gate*                             |

```Z = A OR B```

|A|B|Z|
|:-:|:-:|:-:|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|1|
## Examples

Some examples of possible combinations


### NOR Gate

```Z = NOT(A OR B)```

|A|B|Z|
|:-:|:-:|:-:|
|0|0|1|
|0|1|0|
|1|0|0|
|1|1|0|

```Z = NOT(A) OR B NOT A OR B```

|A|B|Z|
|:-:|:-:|:-:|
|0|0|1|
|0|1|1|
|1|0|1|
|1|1|0|

### NAND Gate

```Z = NOT(A AND B)```

|A|B|Z|
|:-:|:-:|:-:|
|0|0|1|
|0|1|0|
|1|0|0|
|1|1|0|

AND OR Gate

|A|B|C|Z|
|:-:|:-:|:-:|:--:|
|0|0|0|0|
|0|0|1|0|
|0|1|0|0|
|0|1|1|1|
|1|0|0|1|
|1|0|1|1|
|1|1|0|1|
|1|1|1|1|

AND AND OR gate

|A|B|C|Z|
|:-:|:-:|:-:|:--:|
|0|0|0|0|
|0|0|1|0|
|0|1|0|0|
|0|1|1|0|
|1|0|0|0|
|1|0|1|1|
|1|1|0|1|
|1|1|1|1|

For combining gates the order is as follows: 

1.  Brackets ()
2. NOT gate
3. AND gate
4. OR GATE
