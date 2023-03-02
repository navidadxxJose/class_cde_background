CLASS: Cosmic Linear Anisotropy Solving System  {#mainpage}
==============================================


This is the code for coupled vector dark energy model, which includes only the background modification.


The model has got seven parameters ($s, b_{2}, p_{2}, \beta ,Q,  q, \rho_^{DE}_{ini}$). 

We have two options for $\beta$: 1 or 0. 
$\beta=1$ correspond to arXiv:1907.12216v2 while $\beta = 0$ arXiv:2207.13682v1 [astro-ph.CO] 27 Jul 2022. 
The .ini files for $\beta = 0$ are missing.

We fix $q$  and $b_{2}$ in background.c

$s, p$ and, $Q$ are the parameters of the model.  

To run an example with $Q = 0, p=1$ and $s = 0.2$, type 

./class ini_file_cde/beta_1/Q_0/s_02.ini 

In the ini_file_cde/  folder there are four different cases of $Q$ to run the code 
these correspond to  0, 0.2, -0.5, -1

If you want to change the values of s, you can see inside the following files:
ini_file_cde/beta_1/Q_0/
ini_file_cde/beta_1/Q_02/
ini_file_cde/beta_1/Q_05/
ini_file_cde/beta_1/Q_1/

In those files, you will find .ini files with the following values of $s$ to run Class: 1, 0.9, 0.8, 0.7, 0.6, 0.5, 0.4, 0.3, 0.2, 0.1 

The outputs will be saved in output_for_cde/

We have an option to solve numerically a differential equation for dark matter:
\textit{num_sol_cdm_vf = (yes or no)}

In ini_file_cde/beta_1/cdm_num you will find .ini files to execute Class solving numerically cdm.