# -A Python-based project for performing basic quality control and nucleotide composition analysis of DNA sequences.

Overview

DNA sequence data may contain invalid characters or empty sequences that should be identified before downstream analysis. This project implements a simple DNA sequence QC workflow using fundamental Python programming concepts.

The program:

Validates DNA sequences
Identifies empty and invalid sequences
Calculates sequence length
Counts individual nucleotides (A, T, G, C)
Calculates nucleotide composition
Calculates overall GC content
Generates a basic QC report

The project is intentionally implemented using core Python, without Biopython or other specialized bioinformatics libraries.

Input

The program takes a list of DNA sequences as input.

sequences = [
    "ATGCGTACGTA",
    "ATGCCGT",
    "GGCGCGCGCG",
    "ATXCGTAC",
    "ATATATATATAT",
    "GCGTACG",
    "",
    "ATGCGCATGCATGC"
]

The example dataset contains both valid and invalid sequences:

Valid sequences contain only A, T, G, and C
ATXCGTAC contains an invalid nucleotide (X)
An empty string represents an empty sequence
QC Workflow
1. Sequence Validation

Each sequence is checked for valid DNA nucleotides.

Valid:

ATGCGTACGTA

Invalid:

ATXCGTAC

Empty sequences are also treated as invalid.

2. Nucleotide Counting

For each sequence, the number of individual nucleotides is calculated.

For example:

Sequence: ATGCGTACGTA

A = 3
T = 3
G = 3
C = 2
3. Total Nucleotide Composition

The nucleotide counts from the sequences are stored and summed to obtain the total number of each nucleotide in the dataset.

Total A = 16
Total T = 17
Total G = 19
Total C = 16
4. GC Content

GC content is calculated using:

GC% = ((G + C) / Total bases) × 100

For the example dataset:

GC% ≈ 51.47%
Python Concepts Used

This project was developed to practice fundamental Python programming concepts in a bioinformatics context.

Concepts used include:

Variables
Lists
Strings
for loops
Nested loops
Conditional statements
Boolean variables
continue
String methods
.count()
.append()
sum()
Arithmetic operations
Basic sequence-processing logic
