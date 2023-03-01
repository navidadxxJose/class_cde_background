CLASS: Cosmic Linear Anisotropy Solving System  {#mainpage}
==============================================


This is the code for the dark vector energy model that include the background.


The model has got four parameters ($s, p_{2}, Q, and q$) 

To run an example with $Q$ = 0 and $s = 0.2$, type 

./class ini_file_cde/Q_0//s_02.ini 

Look at the ini_file_cde/  folder to see four different cases of $Q$ to execute the code (these correspond to 0, 0.2, -0.5, -1).

If you want to play with the values of s, you can see inside
cd  ini_file_cde/Q_0/
cd  ini_file_cde/Q_02/
cd  ini_file_cde/Q_05/
cd  ini_file_cde/Q_1/

Here, you will find .ini files with the following values of $s$: 1, 0.9, 0.8, 0.7, 0.6, 0.5, 0.4, 0.3, 0.2, 0.1 

The outputs will be saved in output_cde/.  