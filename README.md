# BME-160
Labs completed for Research Programming in the Life Sciences 2022
# BME-160
Labs completed for Research Programming in the Life Sciences 2022. Written in OOP.

Assignments and python programs:
- Manipulating Data Types
    - seqCleaner: Removes ambiguous base (“N”) output from a sequencer.
    - fastqParse: Parses FASTQ sequence file and collects instrument, run ID, flow cell ID, flow cell lane, tile number, and coordinate information.
    - coordinateMathSoln: Building off a premade class, calculates the bond lengths and angles of three sets of atomic coordinates provided in one line.
    - converter: Using dictionary mappings, converts RNA and DNA codons to amino acid symbols.

- ProteinParam
    - Calculates the physical-chemical properties of an input protein sequence. Outputs molecular weight, molar extinction coefficient, mass extinction coefficient, theoretical pI, and amino acid composition (in %).
 
- sequenceAnalysis
    - NucParams: Calculates codon, amino acid, and nucleotide counts for an input nucleotide sequence.
    - addSequence: Accepts additional sequences from input for analysis.
    - aaComposition: Counts number of amino acids in nucleotide sequence.
    - codonComposition: Counts the number times a valid amino acid codon appears in the nucleotide sequence.
    - Calls on ProteinParam class to output additional information about predicted protein.\
    - GenomeAnalyzer.py: Imports sequenceAnalysis module and prints out statistical values of codons, nucleic acids, and amino acids.
