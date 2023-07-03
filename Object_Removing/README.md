# Seam Carving
This project implements content-aware image resizing, which keep interesting parts without deteriorating the quality of the interesting elements when we reduce the width of an image.
## Description
Once we select the region of interest, we make all the seams pass through this region. We do this by manipulating the energy matrix after every iteration. We have used the function called compute_energy_matrix_modified to achieve this. Once we compute the energy matrix, we assign a value of zero to this region of interest. This way, we force all the seams to pass through this area. After we remove all seams related to this region using remove_vertical_seam function, we keep adding the seams until we expand the image to its original width.
## Result
The result is as follows.
<div align="center">
  <img src="./original.png" width="350" height="200">
  <img src="./result.png" width="350" height="200">  
</div>
