---
title: Basic Bit Manipulation
tags: [C, Competitive Coding]
style: fill
color: info
description: Basics of bitwise operators and Bit Manipulation techniques like set bit, clear bit, update bit and get bit codes and logics are specified.
---

Bit manipulation refers to the manipulation of individual bits within a binary representation of data. This can be done using bitwise operators that operate on individual bits of integers. Here are some basic bit manipulations that can be performed using bitwise operators:

- **Bitwise AND (&):** Performs a logical AND operation between corresponding bits of two integers.

    > Example: 5 & 3 will yield 1 (because 5 in binary is 101 and 3 in binary is 011, so the result is 001).

- **Bitwise OR (\|):** Performs a logical OR operation between corresponding bits of two integers.

    > Example: 5 \| 3 will yield 7 (because 5 in binary is 101 and 3 in binary is 011, so the result is 111).

- **Bitwise XOR (^):** Performs a logical XOR (exclusive OR) operation between corresponding bits of two integers.

    > Example: 5 ^ 3 will yield 6 (because 5 in binary is 101 and 3 in binary is 011, so the result is 110).

- **Bitwise NOT (~):** Flips the bits of an integer, changing 0 to 1 and vice versa.

    > Example: ~5 will yield 2 (because 5 in binary is 101, and flipping the bits results in 010, which is the binary representation of 2).

- **Left shift (<<):** Shifts the bits of an integer to the left by a specified number of positions.

    > Example: 5 << 2 will yield 20 (because shifting 5 (101 in binary) two positions to the left results in 10100, which is the binary representation of 20).

- **Right shift (>>):** Shifts the bits of an integer to the right by a specified number of positions.

    > Example: 5 >> 1 will yield 2 (because shifting 5 (101 in binary) one position to the right results in 10, which is the binary representation of 2).

These are some basic bit manipulation operations that can be performed using bitwise operators. They are useful in various applications such as low-level programming, data compression, cryptography, and optimizing algorithms.