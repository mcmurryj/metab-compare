## Synopsis
A simple pipeline for two-way comparative metabalomics using XCMS.<sup>1</sup>    The specific settings are largely based on the SI from  "Six enzymes from mayapple that complete the biosynthetic pathway to the etoposide aglycone." Lau W and Sattely ES, 2015 Sep 11;349(6253):1224-8. doi: 10.1126/science.aac7202.  I added some additional heuristics to try and cut down on the # of spurious peaks, so the resulting pipeline is pretty conservative if you are using 4-5 replicates of each condition.

You will need to alter the variable names ("XXXXX" and "wt") to match your sample names.  Actually I think it will work without changing the variable names but will look stupid.  The commands should be run from within a directory that contains 2 folders. Each folder should contain n mzml files from a given condition, where n is at least 3 and is preferably more like 5.

The little ditty at the end plots chromatograms that seem interesting for  visual scrutinization, which I think is useful.

1.  "XCMS: processing mass spectrometry data for metabolite profiling using nonlinear peak alignment, matching, and identification.", Smith CA, Want EJ, O'Maille G, Abagyan R, Siuzdak G.  DOI: 10.1021/ac051437y
