# Utrecht: Integrated Network Management (INM)
This repository contains the code which was produced during the Master Thesis of Paula Vogg at TU Delft. The project is an extension for public transport of an existing traffic control logic called Integrated Network Management (INM). For the Master Thesis an extensive data analysis with public transport data and system data was performed. ¨
The data analysis is structured in three levels of detail (macro, meso, micro). The codes for the macro and meso analysis are in the folder with the flow data. 
Data files:
- The flow data is obtained from the provided excel files and saved as complete csv files.
- The data from the Arane data portal is obtained with an API in the code. 
- The public transport data from NDOV needs to be retrieved day by day and placed in the NDOV folder (exact instructions in the micro analysis codes). The chosen dataset is called kv6.
