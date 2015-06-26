Number Cards
============

One of the more basic cards are **number cards**. Number cards are
used to introduce constants into a calculation. A number cards is
comprised of two parts. The first part is the column that will store
the number. The second is the actual number itself.

The columns in the store could store fifty decimal digits and could be
signed. An operator would have to punch in leading zeroes to make sure
that the correct number was stored.

Representation
--------------

We will represent a number card with the following syntax. We start
with a `N` followed by a the column index (000 through 999) followed
by a signed fifty digit decimal number.

For example, the following cards

```
N037 +00000000000000000000000000000000000000000000000000
N051 +00000000000000000000000000000000000000000000003435
N128 -00000000000000000000000000000000000000000000001024
```

The first card will zero column 37. The second card will store the
number 3435 on column 51. The third card stores -1024 on column 128.

### Shortcuts

Because it quickly becomes tedious to be so explicit about our number
cards, the following shortcuts were introduced.

You can dispense the leading zeroes and the sign if the number is
positive. The preceding example reduces to

```
N37 0
N51 3435
N128 -1024
```


Excercises
----------

1. Describe in words what the following cards do

```
N000 +00000000000000000000000000000000000000000000000707
N1 73083734
```

2. Write down the representation of the number card that stores your
   favourite number on column with your least favourite index.
3. Did you expect number cards to be part of the analytic engine?
4. What is special about the numbers in this chapter?
