# de-id
Perl and Python code for de-identifying electronic medical records of the category age
# Prerequisites
## Python
* Python 3.5.2
## Perl
* Perl 5, Version 28, Subversion 0 (v5.28.0)
# Running insturctions
## Python Code
### De-identification
1- Change to the python directory

2- run ```python3 deid-Etienne-Nichole.py id.text age-Etienne-Nichole.phi    
```

In which:

* ```id.text``` contains Patient Notes.
* ```age-Etienne-Nichole.phi``` is the output file that will be created.
### Stats
1- change to the python directory

2- run ```python3 stats-Etienne-Nichole.py id.deid id-phi.phrase age-Etienne-Nichole.phi ```

In which:

* ```id.deid``` is the gold standard that is category-blind.
* ```id-phi.phrase``` is the gold standard with the categories included.
* ```age-Etienne-Nichole.phi``` is the test file that the stats is run on.
