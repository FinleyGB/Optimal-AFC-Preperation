Optimal AFC shape calculation & implimentation. 

Creating the AFC teeth in parallel using an optical pulse train. The desired AFC shape can be calculated using just the desired storage time and OD of the QM. 

storage time = tau # storage time of pulse
Delta = 1/tau # spacing between each tooth
Finesse = Delta/gamma

Optimal Finnese and therefore optimal AFC shape can be calculated using F_opt = pi/arctan(2pi/OD)

Repository includes code to control Zurich Instruments HDAWG. There is a python script to talk to the HDAAWG and a sequence written in the LabOne languange saved as a .txt.

optimal_afc_shape_paper.ipynb

This Paper makes many AFCs ar differenct central frequencies in parallel

Towards highly multimode optical quantum memory for quantum repeaters.
Pierre Jobez, Nuala Timoney, Cyril Laplane, Jean Etesse, Alban Ferrier, Philippe Goldner, Nicolas Gisin, and Mikael Afzelius
Phys. Rev. A 93, 032327 – Published 21 March 2016