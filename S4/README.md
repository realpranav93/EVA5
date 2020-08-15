## **Objective:**
To build a Model to acheive a validation accuracy >=99.4% with less than 20k paramters.
 
## **Code block by block:**

**Block1:** Is to load all the necessary libraries to build and train our model. 

**Block2:** Is to define the architecture of our model. Following are the key tools used while designing this architecture: 
- It's a expand and squeeze model. Number of kernels(also translates to number of parameters in a particular layer of a deep numeral network) are increased using 3x3 convolutions and decreased using 1x1 convolutions respectively 
