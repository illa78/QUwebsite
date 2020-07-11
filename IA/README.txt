Last update: 26 June 2013


README

The directory IA includes a set of three Matlab functions is used to analyze the scanned image of a paste, mortar, or concrete sample.

The functions must be run in the following order:

1) readimage
2) basicanalysis
3) reconstructspheres (optional)

To read specific information on how to use these functions, type 'help <function>' at the Matlab command prompt >>, where <function> is the function of interest.   

Two example images are included to help acquaint the user with this program.  Both these images of mortar samples with a paste:solids ratio = 0.8.  If the user wants to analyze the image 'ex1.tif' located in the current working directory, the following commands are an example of how to excecute this analysis:

>> readimage('ex1.tif')

>> basicanalysis(0.8)

>> reconstructspheres(4,150)


AUTHOR

Contact Priscilla Fonseca at pcfonseca@quinnipiac.edu for questions, suggestions, bug reports, or to obtain the latest version.
