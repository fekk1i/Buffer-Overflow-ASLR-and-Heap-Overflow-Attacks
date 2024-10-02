# Exploit Development: Buffer Overflow, ASLR, and Heap Overflow Attacks

This repository contains coursework demonstrating various exploitation techniques, including buffer overflow attacks, bypassing ASLR, and heap overflows, with a focus on modifying control flow, launching shells, and manipulating memory.

## Key Features:
- **Buffer Overflow**: Exploiting stack buffer overflows to execute arbitrary code by overwriting return addresses.
- **ASLR Bypass**: Techniques to disable or circumvent Address Space Layout Randomization (ASLR) for reliable exploitation.
- **Heap Overflow**: Demonstration of heap corruption by overflowing heap-allocated buffers and causing segmentation faults.

## Contents:
- **Exploit Code**: Source code files showing how vulnerabilities are exploited.
- **Report**: Detailed documentation explaining the methodologies, findings, and results for each attack.

## Methodologies Used:
- **GDB Debugging**: Used to inspect memory addresses, function calls, and control execution flow.
- **Memory Layout Analysis**: Explored the layout of stack and heap memory to calculate offsets for exploitation.
- **Payload Construction**: Crafting malicious input strings to overwrite critical memory areas and alter program execution.

## Findings:
- **Buffer Overflow**: Successfully overwrote return addresses to redirect execution to arbitrary functions.
- **ASLR Bypass**: Demonstrated reliable exploitation by disabling ASLR.
- **Heap Overflow**: Induced heap corruption, causing segmentation faults and heap metadata corruption.

## Tools & Technologies:
- **GCC**: Compiling vulnerable programs with/without security features.
- **GDB**: Debugging and memory inspection tool.
- **Python**: For crafting payloads and automating string manipulations.

## Author:
- **Ali Abdelhamid**  
  Coventry University, Cairo, Egypt  
  Email: aa2100274@tkh.edu.eg
