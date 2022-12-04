True invert of 8 bit image - not just inverting LUT

For numerical codes I run, I want background white to be pixel value 255, and object black to be 0

Auto local threshold methods do this, depending of your selection of "White objects on black background"

But the normal global theresholding method, depending of your selection of "Dark background",
just makes it an Inverting LUT, or not: i.e. whether 0 is displayed as white or black.

This is a true inverting method, pixel values 0 replaced with 255, 1 with 254 etc.

Public domain, copyright Prof Phil Threlfall-Holmes, TH Collaborative Innovation, 2022