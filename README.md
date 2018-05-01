# Morphology_singleOp
Single Morphological Operation

1 Input1 (argv[1]): a txt file representing a binary image with header.

 2. Input2 (argv[2]): a txt file representing a binary image of a structuring element 
   with header and the origin of the structuring element. The format of the structuring element is as follows: 
   1th text line is the ordinary image header; the 2nd text line is the position (w.r.t. index) of the origin, 
   then follows by the rows and column of the structuring element.
3. argv[3], as the user's choice of 
which morphological operation to the image binary image in argv[1] 
using the structuring element  in argv[2]. 
The value of argv[3] is a character:
	D for dilation
	E for Erosion
	O for Opening
	C for Closing
4. argv[4], output file
