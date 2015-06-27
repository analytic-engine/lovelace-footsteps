Combinatoric Cards
==================

Although we can calculate the the *number cards*, *variable cards* and
the *operation cards*, we can not really program. What we are missing
are means to branch and loop our program.

**Combinatorial cards** serve the purpose of introducing branching and
looping in our programs. The way they achieve this is by operating on
the card chain.

Up until now the card chain is reading the cards in a consecutive
fashion, one after the other. Combinatorial cards change this by
skipping forward or backward a number of cards. This can happen either
conditionally or unconditionally.

Representation
--------------

A combinatorial card is identified by a `C` followed by either a `F`
or a `B` indicating the the direction to skip.

* `F` Skip forward
* `B` Skip backward

After that follows a flag `+` or `?` to either unconditionally or
conditionally skip.

* `+` unconditionally skip
* `?` skip if the Mills *run-up lever* is set.

Last is the number of cards to skip. To understand this number, it's
important to keep in mind that at the time the card chain is advanced
or backed up, the combinatorial card itself has already been read, and
the Card Reader advanced to the next card in the chain. Therefore, the
starting point for counting how many cards to back or advance is the
card after the combinatorial card, not the card itself.

### Examples

The following cards

```
CF+1
CB?2
```

unconditionally skip forward 1 card and conditionally skip back 2 cards.

Excercises
----------

The following excercise do not ask for full programs but for rough
sketches of the form of the card chain. It will help prepare you for
actual programs.

1. sketch out a if statement
2. sketch out the form of a while loop.


Create and run programs that calculate

3. a factorial of a value on a store column.
4. sum of the first `n` squares.
