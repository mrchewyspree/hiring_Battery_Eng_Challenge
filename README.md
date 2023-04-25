# Batterie Engineering Challenge #

The repository consists of 2 raw datsets and guidelines to develop the 2 tasks, 3rd task is bonnus.
For the first task, it is recommended to use pyhon or matlab. However, the choice of selecting the environment is entirely upto the candidate, in CX we prefer python jupyter notebooks.
Assess the tasks and import whatever the libraries are required for you.

### Task 1:

1. Import the .csv file from the folder. This file consists of initial characterization batterie( Tests performed from 100% to 0%). what is the capacity of the batterie?
2. Analyse the data in detail and extract the parameters of li ion cell equivalant circuit model(ECM). (Assume a 2nd order equivalant circuit model). Hint: try to use current interruption technique to extract the parameters.
3. Extract ocv values of the cell w.r.t SoC and plot the curve.
4. Extract other cell parameters and plot them w.r.t the SoC. hint: You can use any non linear optimization methods to parametrize the ECM model. i.e. scipy library, curve_fit etc.
5. Plot w.r.t time V_actual & V_simulated after building the model with the extracted parameters. 
6. Plot error with respect to time
7. Plot the error distribution.


### Task 2:

1. Import the .xls file from the folder describing the cycling aging charge data at different timeperiods over the life.
2. Data preprocessing shall be done. Look for outliers, missing values if any. Add any additional attribtes for the sake of restructuring the data.
2. Compute the SoC (build a function in python or matlab to compute the soc). Hint: take initial soc from the soc-ocv curve developed in the previous task.
3. Calculate the SoH of the battery for every charge cycle and plot the Charge voltage w.r.t the Capacity. Hint: Overlap all charge curves in a single plot to see the ageing behaviour.


Write a brief report about all assumptions and reasoning together with the plots and functions you developed and upload it into the repository along with the raw code. This report might be a jupyter notbook if it's part of the tools you are using.

### Task 3 (Bonus):

Using field data identify 5 KPIs/indices or more that will give usefull insight of batteries state (keeping energy storage and second life application in mind).

## Things to keep in mind
 
Please understand that this challenge is not decisive if you are applying to work at Circunomics.

This is just an opportunity for us both to work together and get to know each other in a more technical way.

The point is to understand how you set up your approach and which packages you use and how you communicate and present your ideas.

Have fun!


