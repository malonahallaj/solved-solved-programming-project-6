Download Link: https://assignmentchef.com/product/solved-solved-programming-project-6
<br>
Assignment Overview

The goal of this assignment is for you to become more proficient with file I/O and using functions. These concepts will be explored by conducting a historical comparison between the change in GDP and the unemployment rate. Problem Statement In economics, the gross domestic product (GDP) is a measure of how much a country has produced. Economists use this number to gauge how well the economy is doing in a country. The unemployment rate is another measure.

However, the unemployment rate is called a lagging economic indicator because the rate typically does not go down until the economy starts to pick up again. We will provide the ability to print out an average for both values from any year in the range 1948-2008. The unemployment data was obtained from the U.S. Bureau of Labor Statistics and the GDP data from the U.S. Bureau of Economic Analysis.

Program Outline

1. Prompt the user for the GDP file name and the unemployment file name.

2. Prompt the user for a particular year in the range 1948-2008 (for which both sets are complete). Any year outside of that range is considered an error

3. Process each dataset in a separate function.

4. Provide the average GDP and Unemployment rate for the user provided year.

5. Extra Credit (10 pts).

Plot the trends for the two and provide a graph as below. Example Output GDP File Name: gdp.txt Unemployment File Name: uemp.csv Year to examine: 1948 For 1948, average GDP: 4.225 and average unemployment: 3.75 GDP File Name: gdp.txt Unemployment File Name: uemp.csv Year to examine: 2088 Bad year, try again Year to examine: 2008 For 2008, average GDP: -1.825 and average unemployment: 5.808 If you wish to attempt the extra credit, the graph is shown below.

Program Specifications

You project will do the following:

1. Take input from the user, providing file names for the GDP data and the file name for the unemployment data.

2. Prompt for the year to be checked. Do error checking to make sure it is in the range of 1948-2008. If not, reprompt until a good year is provided

3. Create a function that takes a filename of the GDP data and a year as input and outputs the average GDP for the provided year. Note that the format of the file has space separated values and there are 4 entries for each year.

4. Create a function that takes the filename of unemployment data and year and outputs the average for that year. Note that the format of the file has the values separated by commas and that there are 12 values in each year.

5. Provide output for the provided year on the average for the GDP and unemployment as indicated in the example. Extra Credit:

6. Remember that IDLE and plotting don’t always go well together. You may have to work from the console. 7. Your graph should have two different y scales. You should color each line and show which line is which by identifying them on the left and right tick marks, as shown in the example output. It should also have a title, which you can also see in the example output.

Notes and Hints:

• Start with breaking the problem down into parts: input, output and the two functions for the two files. Write the skeleton program for that and see if it runs.

• Make two “dummy” functions that take and yield the correct type of value. The actual

• Now fill in one function for one data set and test it. You can easily figure the values from the files with a calculator to check yourself. Then fill out the other function and test.

• Finally, add error checking for the year.

• For the extra credit.

See these examples (http://matplotlib.sourceforge.net/examples/index.html)f on how to make your graphs, particularly the two_scales.py example. You can also look at Appendix C of the book on angel. Remember, to do this on your home machine you must install matplotlib (which contains pylab) by going to the matplotlib website (http://matplotlib.sourceforge.net/). However, you first need to have numpy (http://numpy.scipy.org/) installed on your computer. Deliverables proj06.py — your source code solution (remember to include your section, the date, project number and comments).