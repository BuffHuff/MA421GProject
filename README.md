# MA421GProject
Data for Arrhenius rate ML project
Ethan Huff
using data from NIST Chemical Kinetics Database: https://kinetics.nist.gov/kinetics/

reactant1 - dissociating reactant integer values
N2 = 1
O2 = 2
H2 = 3
CO2 = 4

activation energy - in kJ/mol

temp - in K

k = A * (T/298)^n * exp(-E_a/RT)

k is rate (cm^3 / molecule * s)
A is pre-exponential factor (pre-exp)
n is temperature exponent (temp-exp)
E_a is activation energy (kJ/mol)
R is universal gas constant (kJ/mol * K)
T is temperature (K)
