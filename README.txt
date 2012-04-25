
    SampleFASTQFiles - Sample a FASTQ file 
    Copyright (C) 2012  Pelin Akan (pelin.akan@scilifelab.se)

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as
    published by the Free Software Foundation, either version 3 of the
    License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of 
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.                  

    For a copy of the GNU Affero General Public License
    see <http://www.gnu.org/licenses/>.

This program samples a FASTQ files by taking a number of reads chosen over the whole file.


Usage 1: SampleFASTQFiles inputfile -l [INT]
It will either prints an l number of reads from the FASTQ file (sampled over the whole file)
-l the number of reads you wish to sample

Usage 2: SampleFASTQFiles inputfile -p [INT]
It will prints p percentage of reads from the FASTQ file (sampled over the whole file)
-p the percentage of the reads you wish to sample (if 10%, enter 10)


