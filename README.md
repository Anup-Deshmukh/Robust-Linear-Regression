# Robust-Linear-Regression

Implementation of two algorithms: 
 - Alternating direction method of multipliers (ADMM) for rank sparsity 
 - Alternating minimization (AM) for robust regression 
 
The jupyter notbook (Robust-LR.ipynb) introduces the problem and then walks you through the code in detail.
The entire optimization routine (including gradient calculation) is implemented from scratch.

Some helpful resources to understand ADMM and AM:
- https://stanford.edu/~boyd/admm.html - Few representative examples of papers and tools  
- https://web.eecs.umich.edu/~fessler/course/598/l/n-06-alt.pdf - From a EECS UMICH course
- https://en.wikipedia.org/wiki/Robust_regression - Broad overview of the robust regression 

Prerequisites:
```
numpy==1.15.4
tqdm==4.26.0
matplotlib==2.2.3
cv2==4.3.0
scipy==1.7.0
sklearn==1.1.0
glob
```

