# ML-KEM (Kyber-512) Ring Arithmetic Simulation

A lightweight, Python-based simulation of the Module Lattice-Based Key Encapsulation Mechanism (ML-KEM) polynomial ring arithmetic, following the FIPS 203 standard. 

This repository serves as a computational proof-of-concept for an academic paper in Discrete Mathematics, exploring the foundational mathematics on post-quantum cryptography and lattice-based security.

```bash
python kyber.py

Execution benchmark logs
============================================================
MATHEMATICAL SIMULATION: ML-KEM (CRYSTALS-KYBER) RING ARITHMETIC
============================================================

[Trial 1]
[+] Key Generation Time  : 0.0722 ms
[+] Encapsulation Time   : 0.0824 ms
[+] Decapsulation Time   : 0.0245 ms

[Trial 2]
[+] Key Generation Time  : 0.0741 ms
[+] Encapsulation Time   : 0.1086 ms
[+] Decapsulation Time   : 0.0237 ms

[Trial 3]
[+] Key Generation Time  : 0.1657 ms
[+] Encapsulation Time   : 0.2862 ms
[+] Decapsulation Time   : 0.0456 ms

[Trial 4]
[+] Key Generation Time  : 0.0556 ms
[+] Encapsulation Time   : 0.0681 ms
[+] Decapsulation Time   : 0.0227 ms

[Trial 5]
[+] Key Generation Time  : 0.0465 ms
[+] Encapsulation Time   : 0.0676 ms
[+] Decapsulation Time   : 0.0245 ms

[Trial 6]
[+] Key Generation Time  : 0.0581 ms
[+] Encapsulation Time   : 0.0658 ms
[+] Decapsulation Time   : 0.0198 ms

[Trial 7]
[+] Key Generation Time  : 0.0495 ms
[+] Encapsulation Time   : 0.0759 ms
[+] Decapsulation Time   : 0.0254 ms

[Trial 8]
[+] Key Generation Time  : 0.0633 ms
[+] Encapsulation Time   : 0.0799 ms
[+] Decapsulation Time   : 0.0216 ms

[Trial 9]
[+] Key Generation Time  : 0.0390 ms
[+] Encapsulation Time   : 0.0573 ms
[+] Decapsulation Time   : 0.0185 ms

[Trial 10]
[+] Key Generation Time  : 0.0388 ms
[+] Encapsulation Time   : 0.0755 ms
[+] Decapsulation Time   : 0.0244 ms

    - Modulus Parameter q: 3329
    - Polynomial Degree n: 256
------------------------------------------------------------
STATUS: Ring arithmetic successfully simulated and validated.
