# TBC-Gen

- TBC-Gen was written by: Ali Gholami                                           |
                          PhD student                                           |
                          Department of Mechanical Engineering                  |
                          Lassonde School of Engineering, York University       |
                          Canada                                                |
                          E-mail : alig90@yorku.ca || gholami.ali90@gmail.com   |


- This app can generate yarn paths for Tubular Braided Composites with different yarn patterns (Diamond, Regular, and Hercules) and geometrical variables.

Five geometrical variables should be defined for generating the yarn path.
-  N = Total numbers of yarns
-  Braid angle in degree
-  Diameter of Mandrel in mm
-  Diameter of Strand in mm
-  Number of turns or Height of TBC in mm (one of them is required. The other one will be calculated based on the other input)

-------------------------------------
- After inputting the variables, you can choose to plot one sample of clockwise and/or counterclockwise yarn path
- The complete set of yarn will be plotted in a separate window
- By choosing "Write to .txt file", five txt files will be written: two clockwise yarn path, two counterclockwise yarn path and one property file, which involves #The properties of the generated yarn path.
- The properties file can be loaded by choosing "Load Properties File", and the yarn paths can be plotted.
- The written CW and CCW files can be loaded again by choosing the "Load" button.
