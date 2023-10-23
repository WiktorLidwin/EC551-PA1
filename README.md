# EC551-PA1
Logic Synthesis Engine

This is a tool for providing basic information about a boolean expression. The user should input the expression as an SOP with digits separated by spaces. Also, you can edit the PLA text file where you can connect inputs(with their inversions) to AND gates and the results to an OR gate. To run from this file enter the text "file" when initially prompted from main. 
1. Return the design as a canonical SOP
2. Return the design as a canonical POS
3. Return the design INVERSE as a canonical SOP
4. Return the design INVERSE as a canonical POS
5. Return a minimized number of literals representation in SOP
a. Report on the number of saved literals vs. the canonical version
6. Return a minimized number of literals representation in POS
a. Report on the number of saved literals vs. the canonical version
7. Report the number of Prime Implicants
8. Report the number of Essential Prime Implicants
9. Report the number of ON-Set minterms
10. Report the number of ON-Set maxterms
11. Number of 2-input gates needed to implement SOP 
12. Number of 2-input gates needed to implement POS


Main handles everything. It contains many functions and definitions followed by a simple and short interface.
