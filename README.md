# QOSF-2023

Hey, there! This is Task 2 of the QOSF-2023 in October! Here is the description:

```
> Task 2 find negative values

Given a list of integer numbers, look for a negative number in the list. Consider an appropriate number of qubits and explain why your proposal is valid for all kinds of numbers in case 

def find_negative_numbers(list[int]:list_number):
    """
    list_number: integer list!.
    Return the True or False depends of the input
    """

    # use a framework that works with quantum circuits, qiskit, cirq, pennylane, etc.
    # consider print your quantum circuit,


Example:
A = find_negative_numbers([1,-3,2,15])
print(A)
“True”

B = find_negative_numbers([1,4,8,11])
print(B)
“False”

B = find_negative_numbers([-15,-14,2,-1])
print(B)
“True”

References:

[1] Deutsch, David, and Richard Jozsa. "Rapid solution of problems by quantum computation." Proceedings of the Royal Society of London. Series A: Mathematical and Physical Sciences 439.1907 (1992): 553-558.
[2] Bernstein, Ethan, and Umesh Vazirani. "Quantum complexity theory." SIAM Journal on computing 26.5 (1997): 1411-1473.
[3] Grover, Lov K. , "A fast quantum mechanical algorithm for database search", Proceedings of the 28th Annual ACM Symposium on the Theory of Computing (1996), arXiv:quant-ph/9605043
```

The algorithm in this repo takes advantage of the Deutsch - Jozsa algorithm for finding whether a function is constant (gives the same output every time regardless of the input) or balanced (outputs different values). 
The algorithm is far from efficient and isn't tested in too many cases ☺️
