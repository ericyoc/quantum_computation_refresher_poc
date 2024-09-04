# Quantum Computation Refresher

## Refresher Description
This refresher provides a comprehensive review on the fundamental concepts and principles of quantum computation. It covers a wide range of topics, from the mathematical foundations to the practical applications of quantum algorithms and circuits. The refresher aims to equip you with a solid understanding of quantum computing concepts and their implementation using popular quantum computing frameworks such as Cirq (Google).

## Refresher Objectives
By the end of this refresher, you will be able to:
- Understand the mathematical foundations of quantum computation, including complex numbers, matrices, and vector spaces
- Grasp the concepts of qubits, quantum states, and quantum gates
- Analyze and visualize quantum states using the Bloch sphere representation
- Implement quantum circuits using the Cirq framework
- Understand and apply quantum algorithms such as Shor's algorithm for factoring composite numbers
- Integrate quantum circuits with classical neural networks for applications such as digit classification

## Prerequisites
- Basic knowledge of linear algebra and probability theory
- Familiarity with Python programming
- Understanding of classical computing concepts

## Refresher Outline
1. **Mathematical Foundations**
   - Imaginary and complex numbers
   - Matrix operations and properties
   - Vector spaces and tensor products
   - Eigenvectors and eigenvalues

2. **Quantum States and Qubits**
   - Dirac notation and quantum states
   - Qubits and superposition
   - Measurement and probability
   - Bloch sphere representation

3. **Quantum Gates and Circuits**
   - Single-qubit gates (Pauli gates, phase gates, Hadamard gate)
   - Multi-qubit gates (CNOT, Toffoli, controlled gates)
   - Quantum circuit design and implementation
   - Entanglement and Bell states

4. **Quantum Algorithms**
   - Shor's algorithm for factoring

5. **Quantum-Classical Integration**
   - Integrating quantum circuit with classical neural network

6. **Practical Application**
   - Implementing quantum circuits using Cirq
   - Quantum simulation

## Connecting Quantum Computation Concepts

Here's the list of connections among the quantum computation concepts, with those topics in <ins>***bold italics underlined***</ins> to denote a topic not covered in the refresher but listed here due to the importance of the topic within quantuam computing:

1. **Imaginary Numbers** are the building blocks of **Complex Numbers**, which are a combination of real and imaginary numbers in the form a + bi.

2. **Complex Numbers** enable various **Operations**, such as addition and multiplication, which follow specific rules in the complex domain.

3. **Operations on Complex Numbers** lead to the concept of **Complex Conjugate**, where the imaginary part of a complex number is negated.

4. **Complex Numbers** can be represented on the **Complex Number Plane**, with the real part on the x-axis and the imaginary part on the y-axis.

5. **Complex Numbers on the Number Plane** can be expressed in **Polar Form**, which represents a complex number using its magnitude and angle.

6. **Polar Form of Complex Number** is related to the **Exponential Form of Complex Number** through Euler's formula, which connects exponential functions with trigonometric functions.

7. **Complex Numbers** are used to construct **Matrices**, which are rectangular arrays of numbers used to represent linear transformations and quantum gates.

8. **Matrices** support various **Operations**, such as addition, scalar multiplication, and multiplication using the dot product.

9. **Operations on Matrices** introduce special matrices, such as the **Identity Matrix**, which has 1s on the main diagonal and 0s elsewhere, and serves as the multiplicative identity.

10. The **Identity Matrix** is used to define the **Inverse Matrix**, which, when multiplied with the original matrix, yields the identity matrix.

11. **Matrices** can also be represented as **Column Vectors**, which are matrices with a single column.

12. The **Complex Conjugate** operation can be applied to a matrix, resulting in the **Complex Conjugate of a Matrix**, where the imaginary parts of the matrix elements are negated.

13. The **Transpose Matrix** is obtained by interchanging the rows and columns of a matrix.

14. A **Unitary Matrix** is a matrix whose inverse is equal to its complex conjugate transpose, ensuring that it represents a valid quantum operation.

15. A **Hermitian Matrix** is equal to its own complex conjugate transpose and has real eigenvalues.

16. **Eigenvectors and Eigenvalues** are concepts associated with matrices, where an eigenvector, when acted upon by a matrix, yields a scalar multiple of itself, with the scalar being the eigenvalue.

17. <ins>***Outer Product***</ins> *is an operation between two vectors that results in a matrix, and it is used in quantum computing to construct quantum gates and density matrices.*

18. **Matrices** are used to represent **Single Qubits in Dirac Notation**, where a qubit state is described using ket notation |⟩.

19. **Single Qubits** can exist in a **Superposition** of multiple states, allowing them to represent a linear combination of basis states.

20. **Measurement of a Quantum System** collapses the superposition of a qubit into a definite state, with probabilities determined by the amplitudes of the states.

21. The **Probability of Measuring a Qubit** in a particular state is related to the amplitudes of the qubit's superposition.

22. **Matrix Notation** can be converted into **Dirac Notation** to represent qubit states and operations.

23. The **Bloch Sphere** is a geometric representation of a single qubit state, with points on the surface corresponding to pure states and points inside representing mixed states.

24. **Qubit Gates**, such as X, Y, and Z gates, are unitary operations that manipulate the qubit states on the Bloch Sphere.

25. When applying quantum gates, the **Global Phase** can be discarded, and only the **Relative Phase** between qubit states is considered.

26. The **Hadamard Gate** is a special qubit gate that creates an equal superposition of basis states.

27. **Phase Gates**, such as the S and T gates, introduce phase shifts to qubit states.

28. The **Inverse of Phase Gates** can be applied to cancel out the phase shifts introduced by the original phase gates.

29. <ins>***Rotation Gates***</ins>, *such as RX, RY, and RZ, are used to perform arbitrary rotations of qubit states around the X, Y, and Z axes of the Bloch Sphere.*

30. **Multiple Qubits** can be combined using the **Tensor Product**, allowing for the representation of multi-qubit states.

31. **Multiple Qubit Gates**, such as CNOT, Toffoli, and Controlled Gates, operate on multiple qubits simultaneously, enabling entanglement and conditional operations.

32. **Entanglement** is a quantum phenomenon where multiple qubits become correlated, such that the state of one qubit cannot be described independently of the others.

33. **Two Qubit Bell States** are specific entangled states that form the basis for quantum communication and cryptography protocols.

34. **Phase Kickback** is a quantum phenomenon where the phase of a controlled qubit is kicked back to the control qubit, enabling certain quantum algorithms.

35. **Superdense Coding** is a quantum communication protocol that leverages entanglement to transmit two classical bits of information using a single qubit.

36. <ins>***Quantum Teleportation***</ins> *is a quantum communication protocol that uses entanglement to transfer the state of a qubit from one location to another without physically transmitting the qubit itself.*

37. **Classical Logical Operations**, such as NOT, AND, OR, and XOR, can be implemented using quantum gates in a quantum circuit.

38. **Quantum Circuits** are composed of quantum gates and measurements, allowing for the implementation of **Quantum Algorithms** and **Applications**, such as quantum search, optimization, and machine learning.

39. <ins>***Quantum Fourier Transform (QFT)***</ins> *is a fundamental quantum algorithm that performs a Fourier transform on the amplitudes of a quantum state, enabling applications such as period finding and quantum phase estimation.*

40. <ins>***Quantum Error Correction***</ins> *is a set of techniques used to protect quantum information from errors caused by decoherence and other noise sources, ensuring the reliability of quantum computations.*

By understanding how each concept builds upon the previous ones, you can gain a comprehensive understanding of the foundations and applications of quantum computing.

## Refresher Materials
- Jupyter notebook with code examples

## Tools and Technologies
- Python programming language
- Cirq quantum computing framework
- TensorFlow for classical machine learning integration
- Jupyter Notebook for interactive coding and visualization

## Refresher Resources
- Cirq Documentation: https://quantumai.google/cirq
- TensorFlow Documentation: https://www.tensorflow.org/
- Quantum Computation and Theory [YouTube] https://www.youtube.com/watch?v=tsbCSkvHhMo
- Quantum Mechanices: Mathematical Basis [YouTube] https://www.youtube.com/playlist?list=PLdgVBOaXkb9Bv466YnyxslT4gIlSZdtjw
- The Map of Quantum Computing - Quantum Computing Explained [YouTube] https://www.youtube.com/watch?v=-UlxHPIEVqA

## Chronological Listing of Notable Quantum Computers (As of June 14, 2024)
The field of quantum computing is rapidly evolving, with new advancements and larger qubit counts being announced regularly. In addition, the performance of quantum computers is not solely determined by the number of qubits, but also by factors such as qubit connectivity, gate fidelity, and error correction techniques

1. **D-Wave One** (2011)
   - Manufacturer: D-Wave Systems
   - Qubits: 128

2. **IBM Q System One** (2017)
   - Manufacturer: IBM
   - Qubits: 20

3. **Intel 49-Qubit Chip** (2018)
   - Manufacturer: Intel
   - Qubits: 49

4. **Rigetti 19Q** (2018)
   - Manufacturer: Rigetti Computing
   - Qubits: 19

5. **Google Bristlecone** (2018)
   - Manufacturer: Google
   - Qubits: 72

6. **IBM Q System One** (2019, updated)
   - Manufacturer: IBM
   - Qubits: 20

7. **IonQ Quantum Computer** (2019)
   - Manufacturer: IonQ
   - Qubits: 160

8. **Honeywell H0** (2020)
   - Manufacturer: Honeywell
   - Qubits: 6

9. **Jiuzhang Photonic Quantum Computer** (2020)
   - Manufacturer: University of Science and Technology of China
   - Qubits: 76

10. **IBM Eagle Processor** (2021)
    - Manufacturer: IBM
    - Qubits: 127

11. **Zuchongzhi 2.1** (2021)
    - Manufacturer: University of Science and Technology of China
    - Qubits: 66

12. **Google Sycamore** (2021, updated)
    - Manufacturer: Google
    - Qubits: 53

13. **Rigetti Aspen-M** (2021)
    - Manufacturer: Rigetti Computing
    - Qubits: 80

14. **IonQ Aria** (2021)
    - Manufacturer: IonQ
    - Qubits: 32

15. **Quantinuum H1-1** (2021)
    - Manufacturer: Quantinuum (formed by the merger of Honeywell Quantum Solutions and Cambridge Quantum)
    - Qubits: 20

16. **NVIDIA DGX Quantum** (2023)
    - Manufacturer: NVIDIA
    - Qubits: 8

17. **IBM Osprey Processor** (2023)
    - Manufacturer: IBM
    - Qubits: 433

## Disclaimer
This material is for educational purposes only.

## License
Copyright 2024 Eric Yocam

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
