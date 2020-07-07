# Mathematical-Optimization-versus-Metaheuristic-Techniques-A-Performance-Comparison-for-the-RDS

The files SP_33N.txt, SP_136N.txt and SP_417N.txt define the data for the 33, 136 and 417 bus power distribution systems, respectively.

The "SP_Configuracion.txt" file defines which system will be executed (33, 136 or 417 bus).

Use the program "repoten.exe" in the command window (which can be opened with the direct link "Run repoten") or when opening "Run repoten" you must type "repoten.exe" and pass 2 arguments:

The "number of iterations" and the "Tabu parameter", then click "enter" to start the simulation.

Thus, to execute the program using the 33 and 136 bus systems, the example must be followed:

------------------------------
repoten.exe 100 5
------------------------------

The previous command solves the problem with 100 iterations and with a tabu parameter equal to 5.

For the 417 bus system, the parameters must be changed, as follows:

------------------------------
repoten.exe 1000 51
------------------------------

The best result was found with 1000 load flow iterations and a Tabu parameter equal to 51.
