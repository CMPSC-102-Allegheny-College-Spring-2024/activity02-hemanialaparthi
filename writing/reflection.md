# Data Types

## Hemani Alaparthi

## Program Output

### What is the output from running the following commands?

- `python demonstrate-variable-limitations.py`

```cmd
The value of a feasible number is 115792089237316195423570985008687907853269984665640564039457584007913129639936

The value of another feasible number is 179769313486231590772930519078902473361797697894230657273430081157732675805500963132708477322407536021120113879871393357658789768814416622492847430639474124377767893424865485276302219601246094119453082952085005768838150682342462881473913110540827237163350510684586298239947245938479716304835356329624224137216
```

- `python compare-variables.py`

```cmd
1.0 is not the same as 1.1
1.0 is the same as 1.0
.33333 + .33333 + .33333 is not equal to 1
.33333333333 + .33333333333 + .3333333333 is not equal to 1
The value of 1/3 is 0.3333333333333333
0.3333333333333333 + 0.3333333333333333 + 0.3333333333333333 is equal to 1
1/3 + 1/3 + 1/3 is equal 1
```

## Program Questions

### Why is it not feasible to perform the computation `2**2**100`?

This is because the value is astronomically huge and it is out of computational reach. The memory of the device can find it hard to run the code.

### What is the value of `1/3` according to the Python language? Why?

The value of 1/3 is 0.3333333333333333. This is because it is when `1/3` it means that 1 is being divided by 3, and when you divide two integers, it does true division. True division will always return a float value. For instance, 1/3 is not represented accurately because it 0.3333333333333333(they are just approximations) while 1/2 is represented as 0.5 because it has a accurate representation.

### Why is the value of `.33333 + .33333 + .33333 == 1` equal to `False`?

When aritmetric addition is done, python produces floating points as binary fractions and as I mentioned above, python produces only approximations so when you add the approximations, you get a approximate value and not an exact one so therefore the arithmetric operation above will produce 0.99999 instead of 1.0.

(Did you remember to add your name?!)