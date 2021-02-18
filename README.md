# Star-Data-Analysis
This programme reads, analyses and plots star data from a text file.

The absolute magnitude is calculated from the formula $$ m - M = 5{log} (\frac{d}{10}) $$

Given the parallax angle $p$ and ${d} = \frac{1}{p}$

After this the programme then plots Absolute Magnitude versus B-V Colour and the number and proportion of red giants, white dwarfs, and main sequence stars are estimated. 

The final plot also displays the luminositys of the data, resembling the Hertzsprung Russell diagram

---
1. Load in star data
2. Create and name arrays to store columns of data from file
3. Populate arrays with data from StarData.txt
4. Check with first value from each column 
5. Plot and add a title and label the axes
6. Perform integer operations to lists
7. Create new absolute magnitude column
8. Plot absolute magnitude versus B-V Colour
9. Use paths to segment data into BV Colour and Absolute Magnitude sets to differentiate between types
10. Plot the paths for each type and highlight each segment
11. Calculate the counts of each type of star from the paths
12. Calculate the approximate percentage of each star type in the data set
13. Calculate Luminosity limits from absolute magnitude limits
14. Create a secondary axis using the luminosity limits
