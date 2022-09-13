# lec-01 - 9/12/2022
## intro to programming / algorithms

## 4 steps of programming:

1. understand problem
2. make a plan (algo.)
3. tell computer plan
4. test/improve

## egg bag problem:

- bag of eggs, how many cartons until empty

### psuedocode:

```js
eggsTaken, cartons = 0
repeat until no more eggs
    take egg
    num eggsTaken++
    if num eggsTaken == 12
        eggsTaken = 0
        cartons++
    else
        return cartons, eggsTaken
```

### or you can be smart and do:

```js
cartons = floor(eggs / 12);
remainder = eggs % 12;
```

## chits problem:

- pull chits from greedy bag

- pull chits that can never explode
