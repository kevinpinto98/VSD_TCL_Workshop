# VSD_TCL_Workshop
This 5-day tcl workshop by vlsi system design (VSD) is intended to familiarize th eparticipants with the fundamentals of tcl scripting and how it can be used in conjunction with open-source EDA tools such as Yosys and opentimer by acting as an interface that takes the input design in the form of a .csv file and generates various reports such as timing in order to gauge if the design can be sent for fabrication.

## Day1: Introduction to TCL and VSDSYNTH Toolbox Usage
During day 1 the main task was writing a shell script (i.e. tclui) which further calls the tcl script (tclui.cl) assuming the correct input (.csv file) is provided else it displays an appropriate message depending on the error.

The main scenarios being covered by the shell scripts in terms of the types of inputs the script can handle have been mentioned in the figure below:
![Program](images/day1/d1_1.png)


A snapshot of the input file (openMSP430_design_details.csv) is indicated below:
![Program](images/day1/d1_2.png)

A glimpse of the interface provided by the tclui command (i.e. tclui shell script) is:
![Program](images/day1/d1_3.png)

## Day 2: Variable Creation and Processing Constraints from CSV
The steps involved in day 2 are summarized in the figure below:
![Program](images/day2/d2_1.png)

The input constraints file (openMSP430_design_constraints.csv) is shown in the image below:
![Program](images/day2/d2_2.png)

The output after setting the appropriate variables to the necessary ibrary files and directories is as follows:
![Program](images/day2/day2_3.png)