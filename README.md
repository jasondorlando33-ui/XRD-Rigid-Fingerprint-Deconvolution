XRD Rigid Fingerprint Deconvolution

\-----------------------------------





**Function/Goal:**

The program takes reference data and fits a region of interest to Guassian or Voigt peaks. These peaks are used to create a composite peak for each reference which is used to fit samples to determine a rough composition controlling for relative response of each sample. The script was created to determine percent composition of crystals forms in XRD for an Anton Paar XRDynamic 500 when Rietveld refinement is not possible. In its current form the code is edited to adjust parameters, and file location. As such it is not currently structured to be an executable application.





**Initial Setup/Running the program:**

\-A directory that contains the project files should be created containing references files containing \*ref\* (this is how the script knows they are the references) and sample files that do not contain this substring. The samples and references that are read are .csv files.

\-Files used are int the default csv export format of the Anton Paar XRDview software.

\-A directory "deconvolution" will be added to the given directory.

\-The script will output to the created directory a PDF file with the peak fitting residuals showing the raw data as a dotted line, the reference peaks used to fit the raw data as solid colored composite peaks, and a red line for total fit which is a sum of the references used to fit the data.





**Things to remember:**

**-------------------**

\-Having the excel file open will cause the program to crash. Closing the file and rerunning the program will fix that issue.

\-Additional runs will overwrite the previous files generated  overwriting.



