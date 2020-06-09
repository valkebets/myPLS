# myPLS
We present myPLS toolbox, a Matlab-based analysis pipeline that uses Partial Least Squares (PLS). 

PLS is a data-driven multivariate statistical technique that aims to extract relationships between two data matrices by maximizing the covariance between the two matrices (McIntosh et al., 2004). 

myPLS deploys Behavior PLS, which aims to optimally relate neuroimaging to behavioral data, by deriving _latent components_ that are weighted linear combinations of the original variables. 

myPLS can be used with different types of neuroimaging data formats : 1D (e.g., region-wise graph metrics), 2D (e.g., correlation matrix) or 3D (e.g., voxelwise cortical volume). Behavioral data is usually 1D (e.g., clinical scores).


### Set up
*Requirements:*

•	SPM for saving results onto volume (https://www.fil.ion.ucl.ac.uk/spm/)

• Slice overlay (slover) to display slice maps (http://imaging.mrc-cbu.cam.ac.uk/imaging/DisplaySlices)

• Function ploterr (Copyright (c) 2008, Felix Zoergiebel) for bar plots (https://www.mathworks.com/matlabcentral/fileexchange/22216-ploterr)


### PLS method
For general descriptions of PLS for medical image analysis, we refer to:

•	Krishnan, A., Williams, L.J., McIntosh, A.R., Abdi, H., 2011. Partial Least Squares (PLS) methods for neuroimaging: A tutorial and review. Neuroimage 56, 455–475. doi:10.1016/j.neuroimage.2010.07.034

•	McIntosh, A.R., Lobaugh, N.J., 2004. Partial least squares analysis of neuroimaging data: Applications and advances. Neuroimage 23, 250–263. doi:10.1016/j.neuroimage.2004.07.020


### Applications
Code from this toolbox has been used in these papers:

*Behavior PLS with brain network-based measures:*

•	Zöller, D., Sandini, C., Karahanoğlu, F.I., Padula, M.C., Schaer, M., Eliez, S., Van De Ville, D., 2019. Large-scale brain network dynamics provide a measure of psychosis and anxiety in 22q11.2 deletion syndrome. Biol. Psychiatry Cogn. Neurosci. Neuroimaging (in press). doi:10.1016/j.bpsc.2019.04.004

•	Zöller, D., Sandini, C., Karahanoğlu, F.I., Padula, M.C., Schaer, M., Eliez, S., Van De Ville, D., 2019. Large-scale brain network dynamics provide a measure of psychosis and anxiety in 22q11.2 deletion syndrome. Biol. Psychiatry Cogn. Neurosci. Neuroimaging (in press). doi:10.1016/j.bpsc.2019.04.004


*Behavior PLS with connectivity measures and different grouping in PLS and resampling:* 

•	Kebets, V., Holmes, A.J., Orban, C., Tang, S., Li, J., Sun, N., Kong, R., Poldrack, R.A., Yeo, B.T.T., 2019. Somatosensory-Motor Dysconnectivity Spans Multiple Transdiagnostic Dimensions of Psychopathology. Biol. Psychiatry (in press). doi:10.1016/j.biopsych.2019.06.013

*Contrast PLS for multivariate analysis of group differences and developmental effects:* 

•	Zöller, D., Schaer, M., Scariati, E., Padula, M.C., Eliez, S., Van De Ville, D., 2017. Disentangling resting-state BOLD variability and PCC functional connectivity in 22q11.2 deletion syndrome. Neuroimage 149, 85–97. doi:10.1016/j.neuroimage.2017.01.064

•	Zöller, D., Padula, M.C., Sandini, C., Schneider, M., Scariati, E., Van De Ville, D., Schaer, M., Eliez, S., 2018. Psychotic symptoms influence the development of anterior cingulate BOLD variability in 22q11.2 deletion syndrome. Schizophr. Res. 193, 319–328. doi:10.1016/j.schres.2017.08.003


### Credits
Code written by Prof. Dimitri Van De Ville, Daniela Zoeller and Valeria
Kebets, with subfunctions borrowed from PLS toolbox by Rotman Baycrest
(https://www.rotman-baycrest.on.ca/index.php?section=84)

These scripts and functions are based on myPLS scripts previously 
published on https://miplab.epfl.ch/index.php/software/PLS


### Updates
•	Release v1.0 (25/09/2019): Initial release of myPLS toolbox


### Bugs and questions
You can ask questions, report bugs or discuss ideas for modifications on this Slack channel: **myplstoolbox.slack.com** <br /> or contact Daniela Zoller at XXXX or Valeria Kebets at valkebets@gmail.com
