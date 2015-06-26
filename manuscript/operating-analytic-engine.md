Operating Analytic Engine
=========================

It is OK to be able to describe cards, but it would be better to see
how the Analytic Engine operates because of them. In this chapter we
will show how to operate the Analytic Engine in the virtual machine.

aes
---

The following steps need to be taken to run a **chain** of cards on
the Analytic Engine.

### Navigation

1. Start the `SPA-Ada-Lovelace` virtual machine.
2. Open a terminal
3. Navigate to the `~/Documents/analytic-engine` directory

### Card Chain

4. Open a editor, e.g. `gedit`.
5. Write down a card chain, one card per line.

```
N000 +00000000000000000000000000000000000000000000000001
+
L000
L000
S001
```

6. Save the file under the `~/Documents/analytic-engine` directory.

### Program

In this directory you should find the `program` directory. It contains
a set of Java classes that emulate the Analytic Engine.

7. To check if everything is set up correctly run `java -cp progam aes -u`
8. To run the Analytic Engine with your chain run

```
java -cp progam aes -t <card chain>
```

For more information on the commandline tool see the full
[documentation page][documentation]

Excercises
----------

1. What does the example program do?
2. What does the `-t` option do?

[documentation]: http://www.fourmilab.ch/babbage/cmdline.html
