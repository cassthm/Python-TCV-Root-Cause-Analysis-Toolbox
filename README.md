# Python-TCV-Root-Cause-Analysis-Toolbox
A program encoded using Python programming language that transform the statistical process control (SPC) using total conditional variance (TCV) algorithm into an executable program, to perform root cause analysis on the input dataset and identify the ranking of the major contributors to the variance in the dataset.

The program won a Silver award in International Research and Symposium and Exposition (RISE) 2020, and a Gold award in International Malaysia-Indonesia-Thailand Symposium on Innovation & Creativity - iMITSIC 2021. The extended abstract of the program is published in a proceeding entitled 'PROSIDING-IMITSIC-2021' on page 52 (URL:https://www.researchgate.net/publication/354329818_PROSIDING-IMITSIC-2021).

The code is kept confidential.

To see how the executable program works, users can download the file named 'TCV_RCA_Tool.exe' and click on 'Simulated Data' button to run the program using automatically generated data. Otherwise, users can import a dataset in the same format as in 'Sample Data.xls'. The imported dataset must contain the same number of rows for each of the data point. 

As an example of the application of the program in the manufacturing industry, assuming that there are 8 machines producing electronic chips, measuring the length, width, and height of the chips to ensure that the products are of constant quality, 'Variable 1', 'Variable 2' and 'Variable 3' represents the dimensions of the electronic chips, while the column of 'CLASS' refers to the machines. As a restriction of the program, each of the machines should record the data for the same number of samples, the program would crash otherwise.
