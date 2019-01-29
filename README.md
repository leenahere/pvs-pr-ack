# Proof – Ackermann majorises all Primitive Recursive (PR) functions

This proof is done in NASA PVS and more or less follows the proofs listed below. This proof was done for the class programming verification at University of Applied Sciences Leipzig.

- [Ackermann Function – George Tourlakis](http://www.cs.yorku.ca/~gt/papers/Ackermann-function.pdf)
- [Ackermann function is not primitive recursive](http://www.cs.tau.ac.il/~nachumd/term/42019.pdf)
- [Termination Lecture 3 - Bigger& Bigger – Jonathan Kalechstain](http://www.cs.tau.ac.il/~nachumd/term/Jonathan.pdf)
- [A Machine Checked Proof that Ackermann's Function is not Primitive Recursive – Nora Szasz](https://pdfs.semanticscholar.org/06e4/23ce7aa485caea6a1aeb883a94d2e8dadfa6.pdf)

You can run the whole proof with the proveit_gh script. Make sure to change the `PVSPATH` to point to your installation of PVS. To run the proofs run the following command:

`./proveit_gh -c pr-ack`
