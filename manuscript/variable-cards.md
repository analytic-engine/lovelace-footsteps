Variable Cards
==============

**Variable cards** transfer numbers from the store to the mill, where
they will be operated upon. A variable cards is compromised of the
parts the type of transfer and the column index that is used.

Representation
--------------

There are three kinds of variable cards. Two kind of cards that
transfer values from the store to the mill and one kind of card that
transfers values from the mill to the store. The different kind of
cards are identified by a letter.

* **L** designates load a value from the store into the mill
* **Z** designates load a value from the store into the mill *and
  zero the corresponding column*
* **S** designates store a value rfom the mill into the store

A number after one of the variable cards is used to represent the
column index (000 through 999).

For example, the following cards

```
L000
Z001
S002
```

1. Transfer the value of column 0 into the mill.
2. Transfer the value of column 1 into the mill and zero column 1.
3. Transfer the value of the mill into the column 2.

### Shortcuts

We are allowed to use the same shortcuts we now from number cards. So
the above example can be reduced to

```
L0
Z1
S2
```

### Primed Variable Cards

For each type of variable card there is a primed variant that
transfers from/to the corresponding primed axis.

Excercises
----------

1. How would you swap two values in the store?
2. Did you expect variable cards to be part of the analytic engine?
