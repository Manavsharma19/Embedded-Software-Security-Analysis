# Embedded-Software-Security-Analysis

This project involves analyzing embedded systems firmware and C programs to identify vulnerabilities, exploit them, and implement security fixes. The assignment also evaluates the effectiveness of widely-used security mechanisms.


**Key Features:
**

**Reverse-engineered firmware binaries** to extract and analyze cryptographic keys and remote login credentials.
Performed **buffer overflow** exploits on C programs to achieve unintended functionality.
Proposed secure coding solutions to fix vulnerabilities in the provided C programs.

Evaluated the effectiveness of security mechanisms such as:
**Canaries**: For detecting stack buffer overflow attacks.
**ASLR**: To randomize memory addresses and hinder exploits.
**NX-bit protection**: To prevent execution of code in non-executable memory regions.
Technologies and Tools Used:

Programming Languages: C, Bash
Tools: Binwalk, Firmwalker, SquashFS-tools, GDB, GCC, Linux utilities (grep, scp)
Operating Systems: Linux, Protostar VM

**How to Use This Repository:**

Clone the repository.
Follow the detailed steps documented to replicate the security analysis and fixes.
Learn about embedded systems security through the provided documentation and scripts.
