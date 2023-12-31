.. _workflow:

=========
Workflow
=========


1. Setup config file
---------------------
ultra_config.ini holds all the configuration parameters for instantiating the telescope simulator and launching the error-budget analysis script. Users are required to set the local data path name for saving analysis results and images. Changing stellar flux parameters, set target contrast, close loop parameters in the config are optional.

2. Running the launcher script
--------------------------------
*harris_mode.py* and *multi_zernike_mode.py* are the main launcher scripts to compute static and dynamic tolerances. Telescope simulator can be changed within these scripts. Running a launcher script generates data stored in a folder named something similar to 2023-10-13T16-59-32_hexringtelescope. The path to these data folder is set using the config_local.ini file in the PASTIS repository. At the end of each run, users get error budget table in a text file format which can be imported as an Latex table.


4. Contribution Guidelines
---------------------------
To contribute to the package, users are required to create a new branch from develop, open a new pull request for bugs, enhancement or suggestion using the branch, rebase and fix any merge conflicts, assign reviewer on their pull request and finall mark it ready to review.