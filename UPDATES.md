# Tracking major changes to MuscleDB

## 16 April 2017
* updated ANOVAs with log2-transformed expression values
* updated gene ontology classifications
* revised incorrect standard error calculations for QUAD, GAS, TA

## 4 April 2017
* switched default view to be for Myod1
* revised default expression plot 
  * barplot --> dotplot
  * added in SE
  * colored expr by tissue type (cardiac, smooth, skeletal)
  * add FPKM label to axis
  * adjusted y-axis label font size
* fixed zoom in PCA, volcano plots
* fixed volcano plot, comparison plot errors from ggplot2 update