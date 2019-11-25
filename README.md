Step 1-generateData.ipynb was used to write bernoulli_X.npy, bernoulli_betas.npy, bernoulli_y.npy.  This file does not have to be run every time, and in fact, it should not be run everytime as revision control will have to retain every update to these .npy files.  

Step 2-'Binomial Distribution.ipynb' is our first attempt at creating the gradient and hessian for future estimation.  However, the first step in this code was to check to see how sklearn performed on our simulated dataset.  It performed very poorly.  I believe there are some issues with the way we are generating out data.

Results_Sketch.xlsx is what our final results should look like.  This is currently mock data.

Note:  Not sure what the file "Optimization.ipynb' does just yet.
