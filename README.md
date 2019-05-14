 [ # Anpr-system ]

<<license recognition system for cars>> 




 Consider a car entering BMSIT & M through the college gate. The gate is closed initially.
There is a camera that takes the image of the number plate of the car.
The project reads the text from the image & extracts the cars number.
The cars number is then looked up through the directory of all the vehicles that are registered and are allowed to enter in to the college premises, 
like the vehicle owned by the faculty, etc. if we find a match, the college gate opens automatically (with the help of some mechanism),
otherwise it stays closed.   
The project is the part of this mechanism.
The project involves the extraction of text from the number plate of a car
With the help of MATLAB.  Here in this project we tried to build an automated system 
That reads the number of a car from the image of the number plate (taken by a camera placed at some position for this purpose).




The process can be divided in to 3 broad steps=

a>> Capturing the Image
       *  Pre-processing
       *  Noise elimination
b>> Image Segmentation
       * Plate Extraction
       * Character Segmentation
c>> Character Recognition
       * Template Matching
       * Record Matching
