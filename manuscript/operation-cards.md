Operation Cards
===============

**Operation cards** determine how the mill operates on numbers.

Axis
----

The mill has are three different columns or **axis** called ingress
axis 1, ingress axis 2 and Egress axis. The two ingress axis are
operated upon and the result will be put on the egress axis.

### Primes axis

Beside each regular axis there are is also a primed axis. These axis
were introduced by Babbage because he wanted to divide a 100 digit
number.

### Run-up lever

During exception execution of a operation the **run-up lever** is used
to signal.

Representation
--------------

The four different operations that the mill can perform, i.e. addition, substraction, multiplication and division are designated by the following symbols

* `+` addition
* `-` subtraction
* `*` multiplication
* `/` division

### Addition

> The values in the two Ingress Axes are added (ignoring the contents
> of the Primed Ingress Axis), and the sum is placed on the Egress
> Axis. If the result of the addition differs in sign from that of the
> first argument, or a carry-out occurs during the addition (resulting
> from an overflow of the 50 digit capacity of the Mill), the run-up
> lever is set.

### Subtraction

> The value in the second Ingress Axis is subtracted from that in the
> first (ignoring the contents of the Primed Ingress Axis), and the
> difference is placed on the Egress Axis. If the result of the
> subtraction differs in sign from that of the first argument, or a
> borrow-in occurs (resulting from an overflow of the 50 digit
> capacity of the Mill), the run-up lever is set.

### Multiplication

> The values in the two Ingress Axes are multiplied (ignoring the
> contents of the Primed Ingress Axis), and the least significant 50
> digits of the product are placed on the Egress Axis, with the most
> significant 50 digits appearing on the Primed Egress Axis. The
> run-up lever is never set due to a multiplication.

### Division

> The value in the first Ingress Axis (least significant 50 digits)
> and the Primed Ingress Axis (most significant 50 digits) is divided
> by the value in the second Ingress Axis. The quotient is placed on
> the Primed Egress Axis and the remainder on the Egress Axis. If the
> quotient is larger than 50 digits or the divisor is zero, the run-up
> lever is set.

Excercises
----------

1. Provide examples of a operations that will set the run-up lever.
2. Did you imagine operation cards to be part of the analytic engine?
