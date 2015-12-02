# chromoR
ChromoR is an R package for analysing chromosomal interactions data (Hi-C data) 

chromoR combines wavelet change point with Bayes Factor, for useful correction, segmentation and comparison of Hi-C contact maps [1].
It provides a user friendly software solution, addressing the entire statistical pipeline required for the analysis of chromosomal interactions data. 

chromoR installation
----------------------
You can download the chromoR 1.0.1 package from this repository (a previous version is avilable on CRAN R)

In order to install chromoR follow the usual installtion steps for R packages:
1. Open your R environment and make sure the following packages are installed: gdata, haarfisz, Matrix
2. Open the command prompt
3. Navigate to the directory where you have saved chromoR
4. Run 'R CMD INSTALL chromoR'
5. Open your R environment and type library(chromoR)
Note: the preprocessing function (BuildCIM) available from chromoR requires python (version > 2.6) to be installed on your computer.
If you are using chromoR for correction, segmentation and comparison this is not required. 

Using chromoR
chromoR is fully documented and includes examples and data for an easy start.
Check out ?BuildCIM, ?CorrectCIM, ?ChromoPDenoise and ?SegmentCIM. You may also download additional data and examples from here

References
[1] Shavit, Y. and Lio', P. Combining a wavelet change point and the Bayes factor for analysing chromosomal interaction data. Molecular BioSystems, 2014. 
[2] Shavit, Y. Algorithms for reconstructing the 3D genome architecture. PhD thesis, October 2015.

For any question or problem contact: ys388@cam.ac.uk
