# candg_at_2014SUPERPOSE- An Excel Visual Basic Program for Fracture Modeling

This directory contains the Excel visual basic code to model fractures based on 
stress superposition method. The program operates on the Excel platform. 
It reads the parameters and structural grid data from an Excel template 
and writes the results to the same template. The program has two additional
routines to import structural grid data in the Eclipse and Zmap formats. 
It also includes two auxiliary modules to prepare a structural 
contour map for display purposes in the background and a module to
prepare rose diagram of the fractures.

The algorithm consists of the following steps:
1. Input structural grid.
2. Calculate curvature  related local stress  tensor cell by cell
using a moving window of selected size
3. Rotate and add local stress tensor to regional far field 
horizontal stress and calculate the composite stress tensor.
4. Use the composite stress tensor and rock mechanical 
properties Of the rock to determine if tensile or shear fractures form.  
Mechanical properties required are 
(i)Young modulus, 
(ii) Internal friction angle, 
(iii) Unconfined compressive strength (UCS) and 
(iv) layer thickness.
5. Write fracture attributes to Excel spreadsheet to 
export or display fractures on the structural contour map.

The excel file with template and code is accompanied by the following pdf files
1-user guide to SUPERPOSE
2-How to run SUPERPOSE 



Reference:

SUPERPOSE- An Excel Visual Basic Program for Fracture Modeling Based on the
Stress Superposition Method. CAGEO-D-13-00489R1
