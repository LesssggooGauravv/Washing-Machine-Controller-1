Design a fuzzy logic controller using Mamdani’s approach to determine the wash time of domestic washing machine, assume that inputs are dirt and grease on clothes. Use 5 descriptor for dirt (i.e., VSD, SD, MD, HD, VHD) and 3 descriptor for grease (i.e., SG, MG, HG) and 5 descriptors for output variable of wash time (i.e., VST, ST, MT, HT, VHT). Use triangular membership functions for fuzzy classes and CoG method for defuzzification operations. The set of rules for fuzzy logic tables are given below.
|         | SG  | MG  | HG  |
| ------- | --- | --- | --- |
| **VSD** | VST | VST | ST  |
| **SD**  | VST | ST  | MT  |
| **MD**  | ST  | MT  | HT  |
| **HD**  | MT  | HT  | VHT |
| **VHD** | HT  | VHT | VHT |

The input grease is given in the scale of 0 to 50, whereas dirt is in the scale 0 to 100. Output should be in the range 0 to 60 min. Write a program to find the wash time in minutes for any value of grease and dirt within the range.

# Fuzzy-Washing-Machine-Controller
This problem requires the design of a fuzzy logic controller to determine the optimal wash time for a domestic washing machine. The controller's output (Wash Time) is dependent on two inputs: the level of "Dirt" and "Grease" on the clothes.
