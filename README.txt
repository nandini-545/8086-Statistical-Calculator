
README.txt

Project Title: Statistical Calculator using 8086 Assembly Language
Course: Computer Organisation and Architecture (EET2211)

Submitted by:
1. Nandini Nayak        Reg No: 2341014107
2. Subhashree Sahoo     Reg No: 2341019161
3. Subhakanta Jena      Reg No: 2341010065
4. Managobinda Pradhan  Reg No: 2341016369

University:
Siksha 'O' Anusandhan (Deemed to be University), Bhubaneswar, Odisha

Description:
This project implements a statistical calculator using 8086 Assembly Language. The calculator takes 3 user-defined integers (0–255) and calculates:
- Maximum
- Mean (Average)
- Median
- Variance

The program uses DOS interrupts for I/O and integer arithmetic for calculations due to the lack of floating-point support.

Files Included:
1. stat_calc.asm       - The source code for the statistical calculator
2. COA_REPORT.pdf      - The official project report
3. README.txt          - This file

How to Run:
1. Open EMU8086 emulator.
2. Load 'stat_calc.asm'.
3. Compile and run the program.
4. Input three numbers (each between 0 and 255) as prompted.
5. The results for max, mean, median, and variance will be displayed.

Note:
- Standard deviation is approximated or skipped due to the absence of floating-point support.
- Sorting is done using a simple bubble sort logic.
