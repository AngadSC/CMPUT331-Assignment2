Assignment 2: Transposition
===========================
A collection of Python scripts implementing the columnar transposition cipher.

a2p1.py - regular columnar transposition (encipher and decipher, integer key)
a2p2.py - columnar transposition encipher (permutation key)
a2p3.py - columnar transposition decipher (permutation key)
a2p4.py - dictionary attack recovering the shared key from ciphertext words

PREREQUISITES
-------------
Python 3.13.6 (Standard Library only)

a2p4.py additionally requires dictionary.txt and imports decipherMessage from
a2p3.py, so all files must be kept in the same directory.

USAGE
-----
Run any problem script from the root directory, for example:
python3 a2p1.py

Each script runs its own assertions on startup and prints nothing if they all
pass. To call the functions directly, load a script interactively instead:
python3 -i a2p2.py
>>> encipherMessage([2, 4, 1, 5, 3], "CIPHERS ARE FUN")


