# On the authenticity of prose writings attributed to Śaṅkara 

Ivan Andrijanić, Department of Indology and Far Eastern studies of the University of Zagreb, Croatia.<br />
Jacek Bąkowski, Institute of Polish Language, Polish Academy of Sciences, Kraków, Poland.<br />

This directory contains code and data for the following paper:
On the authenticity of prose writings attributed to Śaṅkara.

The full paper is available here: https://doi.org/10.60018/AcAsVa.npqm2712 


## Funding
This research was funded in part – covering entire J. B. contribution – by the Poland's National Science Centre, grant number 2021/43/O/HS2/02392.<br />


## Corpus of texts
The folder data/corpus contains all texts used with the General Imposters Framework.


## Unsandhi operation
In data/corpus-unsandhied you will find the original texts before unsandhi operation.<br />
The unsandhi operation was realised with the Sanskrit Sandhi and Compound Splitter developed by Oliver Hellwig & Sebastian Nehrdichi which is available here: https://github.com/OliverHellwig/sanskrit/tree/master/papers/2018emnlp <br />

This operation was performed with Python v3.5.2, TensorFlow v1.8.0.


## Stylometry
Stylometry analysis was performed with the package stylo developed in R by Maciej Eder, Mike Kestemont, Jan Rybicki and Steffen Pielström described in the following paper:

Eder, M., Rybicki, J. and Kestemont, M. (2016). Stylometry with R: a package for computational text analysis. R Journal, 8(1): 107-21. https://journal.r-project.org/archive/2016/RJ-2016-007/index.html

Source code is available here: https://github.com/computationalstylistics/stylo 


## License
This work is published under the CC-BY 4.0 license.
