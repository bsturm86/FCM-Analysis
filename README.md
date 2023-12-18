Manual for using the function ‘FCM Analysis’ in R

To simply run the function you can use ‘ FCM Analysis.R’. The file ‘Script for  FCM Analysis.R’ contains the full script where you can view and work with the complete script.
Before starting the analysis make a directory for all the .csv files. You can make sub-directories per SH-category. When starting the analysis there will be some questions in the console. In total there will be eleven questions for exporting data to excel files and other related questions. Exported excel files will be stored in the chosen working directory, which you selected after the first question. The eleventh question is about the possible scaling used in the FCM. Normally in FCM scores between 0-1, but it might be that you used a different scale for clarity for the stakeholders. If this was 0-5, for example, you can fill in ‘5’ as an answer for question 11. The table with the aggregate of the values of all FCMs will also be stored as a .csv file. 
There is a possibility to export seven excel files to the working directory. The one that start with ‘2. matrix_agg…’ contains the aggregate of all the matrices made by the stakeholders. The first worksheet contains the matrix the counts of the connections made, the second the total sum of the values and the third the average values of the connections. The file with ‘3. value_agg…’ is the exported .csv file with the aggregate of all matrices with the average values.
The next file (‘4. connections_made…’) contains a table with all connections that were made by the stakeholders, with the sending and receiving elements and the number of times the connections were made, the average and sum of the values given to the connections. The files ‘5. aggregate_ci_and_mi…’ and ‘6. individual_ci_and_mi…’ contain the concept and matrix indices of the aggregate matrix (5) and all individual matrices (6). Lastly, in the main directory, the files ‘ind_count_matrices…’ and ‘ind_value_matrices’ are exported. These contain the individual matrices of the stakeholders with the number of times they made a connection (0 or 1) and the value they gave to the connections. 
In ‘Script for FCM Analysis.R’ the script is divided in different chapters. The first three chapters are general. The chapters four to nine are repeated in the section A and B. This is necessary to allow the script to run several times. In general there are nine chapters in the script, concerning selecting the data and the analysis of the data:

1. Selecting the working directory and Questions concerning exporting analyzed data;
2. Loading necessary libraries; 
3. Selecting files;
4. Counting the number of connections in all FCMs;
5. Counting the number of connections per variable;
6. Making a data frame with all the combined values of connections of all FCMs;
7. Concept indices and matrix indices of the combined FCM;
8. Graph of combined FCM;
9. Exporting files

A lot of the actual analysis comes from the R-package ‘FCMapper’, by Shaun Turney. This package has some other functions too, that have not been included in this function. More information can be found at: http://www.fcmappers.net/
If any questions arise with working with the function ‘FCM Analysis’ you can send an e-mail to bsturm13@gmail.com. I will be glad to help.

References
Kosko, B. (1986). Fuzzy cognitive maps. International journal of man-machine studies, 24(1), 65-75.
Glykas, M. (2010). Fuzzy Cognitive Maps. Advances in Theory, Methodologies, Tools and Applications, Series: Studies in Fuzziness and Soft Computing.
Ozesmi, U., & Ozesmi, S. L. (2004). Ecological models based on people's knowledge: a multi-step fuzzy cognitive mapping approach. Ecological Modelling, 176(1), 43-64.

