# MA421GProject
Data for Arrhenius rate ML project
Ethan Huff
using data from NIST Chemical Kinetics Database: https://kinetics.nist.gov/kinetics/

reactant1 - dissociating reactant integer values
N2 = 1
O2 = 2
H2 = 3
CO2 = 4 (CO2 -> CO + O)

activation energy - in kJ/mol

temp - in K

k = A * (T/298)^n * exp(-E_a/RT)

k is rate (cm^3 / molecule * s)
A is pre-exponential factor (pre-exp)
n is temperature exponent (temp-exp)
E_a is activation energy (kJ/mol)
R is universal gas constant (kJ/mol * K)
T is temperature (K)

           NIST Designation          T-range             A        n     Ea      
N2 Data:  1986THI/ROT1102-1105	 	3390 - 6440	K 	   9.86E-05	 	-3.33	 	940
O2 Data:  1961CAM/VAU460-470	 	  3400 - 7500	K 	   4.97E-07	 	-1.00	 	494
H2 Data:  1983COH/WES531	 	       600 - 5000 K	     2.61E-08	 	-0.70	 	437
CO2 Data: 1976EBR/SAN3446	 	        2500-7000 K	   	 2.14E-10	 	 0.50	 	435
