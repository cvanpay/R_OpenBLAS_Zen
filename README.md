# R_OpenBLAS_Zen

## Windows RBlas.dll & RLapack.dll compiled from OpenBLAS 0.3.9 with OpenMP enabled, optimized for AMD Ryzen Zen processors.

### Instructions

1. Navigate to your R bin (typically Program Files\R-X.X.X\bin\x64 and rename your current RBlas.dll & RLapack.dll. 
	1. Name them ORBlas.dll & ORLapack.dll (or something similar, so you can change back if needed).
2. Place the RBlas.dll, RLapack.dll, & libopenblas.dll from this repo into your Program Files\R-X.X.X\bin\x64 folder.
3. Make necessary changes to your Makevars.win (typically in Documents\.R), the one included in the repo is an example.
4. Enjoy multi-threaded, faster BLAS.

### Info
* Compiled within R-4.0.0 for Windows, but also tested to work for R.3.6.X.
* CheckAll.txt includes error checking, including Blas. 
* Folder OpenBLAS includes the dynamic & static libs, along with the headers.