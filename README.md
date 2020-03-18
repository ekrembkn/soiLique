# soiLique
soiLique: A MATLAB® Based Algorithm for Deterministic Soil Liquefaction Analysis
					   
              
									Liquefaction Analysis program. 
Setup Notes:

+ The user can find the setup file in the directory:  /soiLique_setup_web_supported/for redistribution/soilique_web.exe 
+ To setup "soiLique.exe", the user will need Matlab Runtime Environment at least v9.4.
+ Matlab Runtime Environment v9.4 will be downloaded and installed from the internet automatically during the installation.
+ Please be sure that you are connected to the internet during installation procedure for the decent installation.

Using with Matlab: 

+ If the user do not want to setup soiLique, he/she will open it in MATLAB with the help of "soiLique.m" file. 
+ "soiLique.m" is the main file that opens the GUI and uses functions. 

---------------------------------------  !!!! WARNING !!!!-----------------------------------------------

All information, including scientific data, processes and results, presented in this program 
have been prepared for general information only.Anyone using this program for any purposes 
without a professional examination and verification of its feasibility
by a professional engineer, the user should take his/her own risk.

>>>>>>>>>>>>>> All liability belongs to the user.<<<<<<<<<<<<<<<<<
---------------------------------------------------------------------------------------------------------

1) ".m" FILES

-"crr_cpt_suz.m" is a matlab function and calculates CRR-CPT with the theory mentioned in Suzuki et al. 1997.

-"crr_n_fine_func.m" is a matlab function and calculates CRR-Nspt with respect to Fine Content with the theory mentioned in Seed and Idriss, 1971.

-"crr_Vs_func.m" is a matlab function and calculates CRR-Vs1 with the theory mentioned in Andrus and Stokoe, 2000.
-"crr_Vs_func2.m" is a matlab function and calculates CRR-Vs1 based on Fine Content Data with the theory mentioned in Andrus and Stokoe, 2000.
-"csr-func.m" is a matlab function and calculates CSR with the theory mentioned in Seed and Idriss, 1971.

-"ef-sig-func.m" is a matlab function and calculates vertical overburden pressure and effective vertical overburden prossure.

-"ishi_yosh_func.m" is a matlab function and calculates settlements with the theory mentioned in Ishihara and Yoshimine, 1992.

-"sf_func.m" is a matlab function and calculates Safety Factor. 

-"toki_seed.m" is a matlab function and calculates settlements with the theory mentioned in Tokimatsu and Seed, 1987.

-"soiLique.m" is the original matlab file for GUI. 

2) "  *.txt" FILES

All txt files, except starting with "Liq_", includes digitised data of graphs of corresponding theories. The files starting with "Liq_" are the result files as samples.  


---------------------------------------  !!!! WARNING !!!!-----------------------------------------------

All information, including scientific data, processes and results, presented in this program 
have been prepared for general information only.Anyone using this program for any purposes 
without a professional examination and verification of its feasibility
by a professional engineer, the user should take his/her own risk.

>>>>>>>>>>>>>> All liability belongs to the user.<<<<<<<<<<<<<<<<<
---------------------------------------------------------------------------------------------------------
