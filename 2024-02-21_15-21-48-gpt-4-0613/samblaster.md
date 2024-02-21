# Samblaster

Samblaster is a fast and flexible program for marking duplicates in read-id grouped, coordinate-sorted sam files. It comes as an open-source software developed explicitly as a tool to remove PCR duplicates from next-generation sequencing (NGS) alignment files. The software is known for its speed, resource utilization, and accuracy, making it an appealing alternative to other duplicate readers in the field.

## Core Features

- **Elimination of Duplicates**: Samblaster excels in eliminating the PCR duplicates from NGS files.
- **Split-Read Detection**: It has provisions to detect 'split'/'disc' alignments in the SAM file.
- **Fast Operation**: It can process ~167,000 read-ids/second using <500MB of memory.
- **SIMD Instructions**: The software leverages SIMD instructions to attain high processing speeds.
- **Clip-Split Overlap**: Samblaster has an option to output vcfs of the split-read and/or discordant pairs it finds into a file.

## Tags
Bioinformatics, Sequence Analysis, Duplicate Marking, PCR duplicates, Open Source, NGS

## Research Discipline
Computational Biology, Bioinformatics, Genomics

## Research Area
Next-generation sequencing data analysis, Genome Sequencing

## Software Class
Open Source Software

## Software Type
Bioinformatics/Computational Biology Software, Sequence Analysis

[Software Homepage](https://github.com/GregoryFaust/samblaster)

Additional Resources:
- [Samblaster README Documentation](https://github.com/GregoryFaust/samblaster/blob/master/README.md)
- [Samblaster Tutorial Blog](https://biofinysics.blogspot.com/2014/05/how-does-samblaster-work.html)
--------------------------------------
