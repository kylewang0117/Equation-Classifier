This is the second subset of the offline handwritten mathematical expressions (HME) dataset for the Task 1. The data uses formula labels of the CRHOME 2012, 2013, and 2014 data. The HMEs in this subset are annotated at symbol level: the latex transcripts, the corresponding label graph and bounding boxes of symbols will be provided.

======================================================
[File Format]


The data set consists of the following four parts:

test2012
test2013
test2014
train2014

For the correspondence between the serial number in the folder and the file, see (* NO._file.txt).

======================================================
[Files in Each Folder]


Each folder contains two files:

img: 	 Scanned image of handwritten formula
OUTPUT:  LaTeX format label, symbolic LG format label and symbol position for the formula image

======================================================
[Important Note]


Although we spent a lot of manpower and resources to ensure the quality of the data, we need to make the following declaration:

1. Formulas with conflicting nodes (objects in the LG file) in the CROHME dataset are not marked

2. In the LG files of the original dataset, the superscript and subscripts of the symbols such as "\sum", "\int", and "\lim" are inconsistent. Some samples use Sup and Sub, while others use Above and Below. To cope with this problem, we normalized a part of the related formulas to Sup and Sub, but there are still about 300 formulas that are not processed.
The list of files that have been modified by scripts and manually can be found in each folder (* fix.txt), and you can contact us when you encounter related problems.

3. For the relevant samples of point 2, their upper and lower marks can be written directly above or below.  The LG files in this dataset uniformly use Sup and Sub to represent these spatial relationships. An example can be found in the example.png file in this folder.

4. Some labels of the original dataset have a problem of inconsistency between "..." and "\ldots". A list of related files (possibly incomplete), see ell.txt.

======================================================
[Missing Files]


The number of files in each folder is less than the number of files in the original dataset. 

1. As in the [Important Note], formulas with conflicting nodes in LG format label in the original dataset are not used.

2. Wrongly written formulas or formulas that exceed the prescribed writing area are not used


======================================================

