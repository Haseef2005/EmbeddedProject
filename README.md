# EmbeddedProject
This repo is about counting number of fish in the fish tank by the image from camera.
The technique that we choose is DBSCAN you can see it in the lower part of ipyng file. 
Start from
  - get the coordiate of the image(already provided function)
  - get segment image from coordinate(alreadh provided function)
  - using DBSCAN to count number of blue bottle cap
*** Parameter eps and min_samples, I have manually choose by myself to detect the cluster. You can try adjust it
You can also see other implementation like Hough Circle in the upper part of ipynb file
