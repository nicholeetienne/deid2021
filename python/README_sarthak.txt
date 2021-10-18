The directory has the original codes and codes modified by Sarthak Satpathy for the BMI-500 Assignment.
     1	date_extra.phi : Detected Date PHI from deid_sarthak_extra.py
     2	date_main.phi : Detected Date PHI from deid_sarthak_main.py (for Evaluation)
     3 	deid.py : Code provided by Dr. Clifford's team
     5	deid_sarthak_satpathy_extra.py : Script with changes to improve the detection in date_main.phi
     6	deid_sarthak_satpathy_main.py : Main modified code with Date Category identification (for evaluation)
     7	id.deid : Used as input for stats
     8	id-phi.phrase : Used as input for stats; Gold Standard for comparison
     9	id.text :  The medical text file for input in the deidentification algorithm
    10	phone.phi : Output from the deid.py file.
    11	README_sarthak_satpathy.txt : this file
    13	stats_sarthak_satpathy_extra.txt : Output Stats for Detected Date PHI from deid_sarthak_extra.py
    14	stats_sarthak_satpathy_main.txt : Output Stats for Detected Date PHI from deid_sarthak_main.py (for Evaluation)
    15	stats.py: Script that generates statistics for evaluating the deid scripts

Please note that for the assignment I have tried implementing 2 functions. deid_sarthak_main.py has the one which detects the dates but has large number of False positives. deid_sarthak_extra.py is similar to the main script but has a few steps to reduce the False positives. The specificity and sensitivity are good 
