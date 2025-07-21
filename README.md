# Schmidt_Lab_Photometry_Analysis

Custom R script to process behavior- or infusion-evoked changes in fluorescence using fiber photometry in freely moving animals. 

RZ processor was integrated with med-associates behavior chambers using the iCON control interface. A custom closed-looped experiment was designed in Pynapse (Tucker Davis Technology, TDT), a Python based programming environment, to control behavior boxes, record data, and time stamp behavioral events. 

Raw signal (465 nm)/isosbestic control (405 nm) channel data and behavioral data were exported from Synapse to a CSV file using a MATLAB script provided by TDT, then imported in R to be analyzed using this pipeline. 

'ICON data analysis' script was used to analyze behavior-evoked changes in fluorescence. 'Acute infusion analysis' script was used to analyze infusion-evoked changes in fluorescence.
