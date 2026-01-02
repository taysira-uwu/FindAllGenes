# FindAllGenes Java Project

## Description
This project is a practical application developed during the course "Java Programming: Solving Problems with Software" from Duke University.  
It demonstrates the skills I gained throughout the course in algorithmic thinking, string manipulation, and problem-solving in Java.

The program identifies all genes in a DNA strand.  
A gene is defined as a sequence that starts with the start codon `ATG` and ends with the nearest valid stop codon (`TAA`, `TAG`, or `TGA`) such that the length of the sequence is a multiple of 3.

---

## Skills Applied
- Understanding and implementing loops and conditionals
- Working with strings and substring extraction
- Designing methods for modular programming
- Debugging and testing algorithms
- Applying logic to solve real-world bioinformatics problems

---

## Features
- Finds multiple genes within a single DNA strand
- Handles DNA strands of any length
- Ignores DNA sequences without valid genes
- Portable and runnable on any Java IDE (Jvdroid, IntelliJ, Eclipse, etc.)


---

## Example Output
Testing on DNA: ATGATCTAATTTATGCTGCAACGGTGAAGA
ATGATCTAA
ATGCTGCAACGGTGA

Testing on DNA: 
(no output)

Testing on DNA: ATGATCATAAGAAGATAATAGAGGGCCATGTAA
ATGATCATAA
ATGT

---

##Project Structure

• FindAllGenes.java: Main program file containing all methods for gene finding and testing.

• main() method: Entry point to run tests and print genes.
