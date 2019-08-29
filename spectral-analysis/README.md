This folder contains notebooks about entity embedding (or categorical feature encoding), based on various spectral methods. 
Using [laplacian method](spectral-encoding-of-categorical-features.ipynb) we were able to achieve good results, 
although not for the case when the categories are not balanced. For that a better choice would be to use [PCA or KernelPCA](PCA.ipynb) 
methods. For completeness we added [t-SNE-based embedding](t-SNE.ipynb), which sometimes produces better results than KernelPCA.
