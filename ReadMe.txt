Provided here are 3 scripts critical for the reproduction of the results found in the manuscript. 

1. Alignment in Unix (“Alignment script.tex”)
This script reproduces the alignment conditions and Uinx command line inputs for extracting, aligning, and counting reads from FASTQ files which can be found in the Immport database.

2. Background correction using R (“data matrix and background correction.tex”)
This script provides the R commands inputted to turn the outputs from the alignment script into a single data matrix that was background corrected as described in the Online Methods. The matrix resulting from this script is provided as a csv file (“Expression Matrix.csv”)

3. Single cell clustering using R (Seurat-Clustering script.tex”)
This script provides the input to recreate the clustering used for all downstream analysis. Use the provided expression matrix or create a new one using scripts 1 and 2.

