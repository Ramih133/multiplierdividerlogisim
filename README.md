# multiplier divider logisim
This repository contains solutions for Assignment 3 of ELEC4480: Digital Computer Architecture, involving the design and testing of digital circuits using Logisim Evolution.

 Overview of Assignment
1. **Parallel Unsigned Binary Array Multiplier**  
   - Combinational \( n \times n \) multiplier for unsigned binary numbers \( A \) and \( B \), using ripple carry adders.  
   - Files: `SID_3a.circ`, `SID_3.txt`.

2. **Wallace Tree Unsigned Multiplier**  
   - \( n \times n \) Wallace tree multiplier with reduced adders for partial products.  
   - Files: `SID_3b.circ`, `SID_3.txt`.

3. **Parallel Unsigned Binary Divider**  
   - \( n \)-bit divider using the restoring division algorithm, outputs quotient \( Q \) and remainder \( R \).  
   - Files: `SID_3c.circ`, `SID_3.txt`.

### Testing and Validation
- Test circuits compare designs with built-in Logisim components.
- Outputs \( P \), \( Q \), and \( R \) are verified using counters and stabilization registers.
