# Teleporting-Hadamad-Information

In this algorithum I have taken input as Superpostion state comprising of 1 qubit information into 2 qubit using Hadamad Gate.

This information later is then passed thorugh Teleportation protocols.

The Teleportation Protocol suggest us:
1. Creating an EPR (Einstein–Podolsky–Rosen) pair of the destination qubit and the medium through which it could be telported.
2. After entangling, we measure the medium of the pair with respect to the source, whose information is to be transfered.
3. After measuring the Information to be transfered, we then measure the information that has been teleported with help of entanglement.
4. We use Pauli X-Gate and Pauli Z-Gate to measure the destination output. Which gives us the teleported information for any state of superpostion of the entangled medium.

## Input
<img width="161" alt="Screenshot 2022-01-10 at 12 37 49 PM" src="https://user-images.githubusercontent.com/69144860/149150263-42e10706-dba9-4aee-8f83-2ccee5cc1675.png">

Here the input q0 = (1/√2)( |0> + |1> )

## Output

<img width="468" alt="Screenshot 2022-01-10 at 12 38 11 PM" src="https://user-images.githubusercontent.com/69144860/149150769-6dffa044-6a08-4fbc-a4f7-2cf2a7f8f32b.png">

Now we see thet last qubit displayed in histogram is the q2. The q2 shows 0.499 (almost 50%) probablity of |0> and 0.501(almost 50%) probablity of |1> for any possiblity of q0 and q1.

This implies that for the information of q0 is successfully teleported to q2. We also observe that the very act of bell measurement of q0 wrt q1 as destroyed the information of q0 but is fully restored into q2.
